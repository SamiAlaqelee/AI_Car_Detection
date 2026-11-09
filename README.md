# 🚗 AI Car Detection & Tracking System
# نظام اكتشاف وتتبع السيارات باستخدام الذكاء الاصطناعي


## 13. Author | صاحب المشروع

**Student Name | اسم الطالب:**

سامي إسماعيل علي علي العقيلي

**English Name:**

Sami Ismail Ali Ali Al-Aqeeli

**Project Title | عنوان المشروع:**

AI Car Detection & Tracking System

**Field | المجال:**

Artificial Intelligence & Computer Vision

**المجال بالعربية:**

الذكاء الاصطناعي والرؤية الحاسوبية

**Project Type | نوع المشروع:**

Practical Artificial Intelligence Project

مشروع تطبيقي في الذكاء الاصطناعي

**Developed by | عمل الطالب:**

سامي إسماعيل علي علي العقيلي

Developed by: Sami Ismail Ali Ali Al-Aqeeli

**Computer Vision | Deep Learning | YOLOv11 | Python | OpenCV | ByteTrack**

---

## 1. Project Overview | نظرة عامة على المشروع

### English
AI Car Detection & Tracking is a Computer Vision project designed to detect and track vehicles in images and videos using Artificial Intelligence and Deep Learning.

The project uses the pretrained YOLOv11 model for object detection and ByteTrack for tracking vehicles across video frames.

It aims to demonstrate practical applications of AI in vehicle detection and intelligent traffic monitoring.

### العربية
مشروع اكتشاف وتتبع السيارات هو مشروع في مجال الرؤية الحاسوبية (Computer Vision)، يهدف إلى اكتشاف السيارات والمركبات وتتبع حركتها باستخدام الذكاء الاصطناعي والتعلم العميق.

يعتمد المشروع على نموذج YOLOv11 لاكتشاف المركبات داخل الصور والفيديوهات، ويستخدم خوارزمية ByteTrack لتتبع حركة المركبات عبر إطارات الفيديو.

يهدف المشروع إلى تطبيق تقنيات الذكاء الاصطناعي في أنظمة مراقبة الطرق وتحليل حركة المرور.

---

## 2. Project Objectives | أهداف المشروع

### English
- Detect vehicles in images.
- Detect vehicles in video files.
- Identify different vehicle categories.
- Track vehicles across video frames.
- Save processed images and videos.
- Explore practical Computer Vision applications.

### العربية
- اكتشاف السيارات داخل الصور.
- اكتشاف المركبات داخل ملفات الفيديو.
- التعرف على أنواع مختلفة من المركبات.
- تتبع المركبات أثناء حركتها في الفيديو.
- حفظ الصور والفيديوهات بعد المعالجة.
- تطبيق مفاهيم الرؤية الحاسوبية عملياً.

---

## 3. Main Features | المميزات الرئيسية

| Feature | الميزة |
|---|---|
| Image Detection | اكتشاف السيارات في الصور |
| Video Detection | اكتشاف السيارات في الفيديو |
| Vehicle Classification | تصنيف أنواع المركبات |
| Object Tracking | تتبع الأجسام |
| ByteTrack | تتبع المركبات عبر الإطارات |
| Result Saving | حفظ النتائج بعد المعالجة |

---

## 4. Technologies Used | التقنيات المستخدمة

| Technology | Description | الوصف |
|---|---|---|
| Python | Programming Language | لغة البرمجة |
| YOLOv11 | Object Detection Model | نموذج اكتشاف الأجسام |
| Ultralytics | YOLO Framework | إطار عمل YOLO |
| OpenCV | Image and Video Processing | معالجة الصور والفيديو |
| NumPy | Numerical Computing | العمليات الحسابية والمصفوفات |
| ByteTrack | Object Tracking | تتبع الأجسام |
| Deep Learning | AI Model Technology | تقنية التعلم العميق |

---

## 5. Supported Classes | أنواع المركبات

The project uses COCO object categories supported by the pretrained YOLO model.

يستخدم المشروع فئات الأجسام الموجودة في مجموعة بيانات COCO والمدعومة من نموذج YOLO المدرب مسبقاً.

| Class ID | Object | النوع |
|---|---|---|
| 2 | Car | سيارة |
| 3 | Motorcycle | دراجة نارية |
| 5 | Bus | حافلة |
| 7 | Truck | شاحنة |
| 0 | Person | شخص |
| 1 | Bicycle | دراجة هوائية |

---

## 6. How the System Works | كيف يعمل النظام؟

### Step 1: Input Data | إدخال البيانات
The system receives an image or a video as input.

يستقبل النظام صورة أو فيديو ليبدأ عملية المعالجة.

### Step 2: Model Loading | تحميل النموذج
YOLOv11 is loaded to perform object detection.

يتم تحميل نموذج YOLOv11 المسؤول عن اكتشاف المركبات والأجسام.

### Step 3: Object Detection | اكتشاف الأجسام
The model analyzes the input and identifies objects using bounding boxes.

يقوم النموذج بتحليل الصورة أو الفيديو وتحديد أماكن الأجسام باستخدام المربعات المحيطة (Bounding Boxes).

### Step 4: Object Tracking | تتبع الأجسام
ByteTrack assigns tracking IDs to detected objects across video frames.

تقوم خوارزمية ByteTrack بإعطاء معرفات (IDs) للأجسام المكتشفة ومتابعة حركتها عبر إطارات الفيديو.

### Step 5: Save Results | حفظ النتائج
The processed results can be saved as images or videos.

يمكن حفظ الصور والفيديوهات بعد إضافة نتائج الاكتشاف والتتبع إليها.

---

## 7. Installation | تثبيت المشروع

### Requirements | المتطلبات

- Python 3.8 or later (حسب توافق إصدارات المكتبات).
- pip.
- Required Python libraries.
- A computer capable of running the YOLO model.

### Step 1: Clone the Repository | تحميل المشروع

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Enter the Project Folder | الدخول إلى مجلد المشروع

```bash
cd AI_Car_Detection
```

### Step 3: Create a Virtual Environment | إنشاء بيئة افتراضية

```bash
python -m venv .venv
```

### Step 4: Activate the Environment | تفعيل البيئة

```bash
.venv\Scripts\activate
```

### Step 5: Install Dependencies | تثبيت المكتبات

```bash
pip install -r requirements.txt
```

---

## 8. Image Detection | اكتشاف السيارات في الصور

### English
The following code loads the YOLOv11 model and detects cars in an image.

### العربية
يقوم الكود التالي بتحميل نموذج YOLOv11 ثم تحليل صورة لاكتشاف السيارات الموجودة فيها.

```python
from ultralytics import YOLO

# Load the YOLOv11 model
# تحميل نموذج YOLOv11
model = YOLO("yolo11s.pt")

# Detect cars in an image
# اكتشاف السيارات في الصورة
results = model.predict(
    source="images/car.jpg",
    conf=0.35,
    iou=0.55,
    imgsz=1280,
    classes=[2],
    max_det=100,
    line_width=1
)

# Display the detection results
# عرض نتائج الاكتشاف
results[0].show()
```

### Parameters | شرح الإعدادات

| Parameter | English | العربية |
|---|---|---|
| source | Input image path | مسار الصورة |
| conf | Confidence threshold | حد الثقة |
| iou | Intersection over Union threshold | معيار التداخل |
| imgsz | Image processing size | حجم معالجة الصورة |
| classes | Selected object classes | الفئات المطلوبة |
| max_det | Maximum detections | الحد الأقصى للاكتشافات |
| line_width | Bounding box thickness | سماكة مربع الاكتشاف |

---

## 9. Video Detection & Tracking | اكتشاف وتتبع السيارات في الفيديو

### English
This code uses YOLOv11 with ByteTrack to detect and track vehicles across video frames.

### العربية
يستخدم هذا الكود نموذج YOLOv11 مع خوارزمية ByteTrack لاكتشاف المركبات ومتابعتها أثناء حركتها في الفيديو.

```python
from ultralytics import YOLO

# Load the model
model = YOLO("yolo11s.pt")

# Detect and track vehicles in a video
results = model.track(
    source="videos/traffic2.mp4",
    conf=0.35,
    iou=0.55,
    imgsz=1280,
    classes=[0, 1, 2, 3, 4, 5, 7],
    tracker="bytetrack.yaml",
    persist=True,
    show=True,
    save=True,
    line_width=1
)
```

### Tracking Parameters | إعدادات التتبع

| Parameter | Description | الشرح |
|---|---|---|
| tracker | Tracking algorithm | خوارزمية التتبع |
| persist | Maintain tracking IDs | المحافظة على معرفات التتبع |
| show | Display video | عرض الفيديو |
| save | Save processed video | حفظ الفيديو المعالج |
| conf | Detection confidence | درجة الثقة |

---

## 10. Project Structure | هيكل المشروع

```text
AI_Car_Detection/
│
├── images/
│   ├── car.jpg
│   └── car2.PNG
│
├── videos/
│   └── traffic2.mp4
│
├── outputs/
│
├── yolo11s.pt
│
├── requirements.txt
│
├── .gitignore
│
└── README.md
```

Note: This is an example structure. Your actual project files may have different names or additional folders.

ملاحظة: هذا مثال توضيحي لهيكل المشروع، وقد تختلف أسماء الملفات والمجلدات حسب تنظيم مشروعك الفعلي.

---

## 11. Model Information | معلومات النموذج

### English
This project uses the pretrained YOLOv11 Small model (`yolo11s.pt`) provided by Ultralytics.

The model has already been trained on a large dataset and is used here for practical object detection.

### العربية
يعتمد المشروع على نموذج YOLOv11 Small المدرب مسبقاً، والذي توفره مكتبة Ultralytics.

النموذج مدرب مسبقاً على مجموعة بيانات كبيرة، ونستخدمه في هذا المشروع لتنفيذ مهام اكتشاف الأجسام والمركبات.

**Important | ملاحظة مهمة:**

This project uses a pretrained model. It does not train YOLOv11 from scratch.

المشروع يستخدم نموذجاً مدرباً مسبقاً، ولا يقوم بتدريب YOLOv11 من الصفر.

---

## 12. Future Improvements | التطويرات المستقبلية

### English
- Vehicle counting.
- Traffic density analysis.
- Lane Detection.
- Traffic flow monitoring.
- Integration with intelligent transportation systems.
- Building a complete Smart Car Vision system.

### العربية
- حساب عدد السيارات والمركبات.
- تحليل كثافة حركة المرور.
- اكتشاف مسارات الطريق (Lane Detection).
- مراقبة تدفق المركبات.
- الربط مع أنظمة النقل الذكية.
- تطوير نظام متكامل للرؤية الذكية للسيارات (Smart Car Vision).

---

## 13. Author | صاحب المشروع

**Field:** Artificial Intelligence & Computer Vision

**Project Type:** Practical AI Project

**Main Focus:** Vehicle Detection and Tracking

**المجال:** الذكاء الاصطناعي والرؤية الحاسوبية

**نوع المشروع:** مشروع تطبيقي في الذكاء الاصطناعي

**التخصص:** اكتشاف وتتبع المركبات

---

## 14. License | الترخيص

This project is intended for educational, research, and portfolio purposes.

هذا المشروع مخصص للأغراض التعليمية والبحثية وبناء معرض الأعمال (Portfolio).

---

⭐ If you find this project useful, feel free to explore and learn from it.

⭐ إذا وجدت المشروع مفيداً، يمكنك الاطلاع عليه والاستفادة منه في تعلم تطبيقات الذكاء الاصطناعي والرؤية الحاسوبية.
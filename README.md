### Overview of the HAM10000 Dataset
Source: [Skin Cancer MNIST: HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

*Disclaimer: The image dataset is not included in this repository due to storage limitations. To view or download the image dataset, visit the link above.*

The HAM10000 (Human Against Machine with 10000 training images) dataset is a large collection of multi-source dermatoscopic images of common pigmented skin lesions. This dataset was released to facilitate the training of machine learning algorithms in dermatology. The dataset contains 10,015 dermatoscopic images, which serve as a representative collection of all important diagnostic categories in the realm of pigmented skin lesions. These images were collected from diverse populations and are annotated with labels for seven different types of skin lesions.


*The dataset is primarily used for:*
- Developing and benchmarking algorithms for the automated diagnosis of skin cancer.
- Comparing human and machine performance in dermatoscopic image analysis.
- Educating and training dermatologists in recognizing various skin lesions.

<br>

### Understanding Skin Cancer and the Role of Deep Learning in Its Detection

Skin cancer is one of the most prevalent forms of cancer globally, affecting millions of individuals each year. It occurs when skin cells undergo uncontrolled growth, often due to prolonged exposure to ultraviolet (UV) radiation from the sun or tanning beds.

Early detection of skin cancer is crucial as it significantly increases the chances of successful treatment and reduces the risk of severe complications or death. Traditionally, detection involves visual examinations, dermoscopy, biopsy, and histopathological analysis, all of which require significant time, resources, and expertise.

In recent years, deep learning, a branch of artificial intelligence (AI), has made significant strides in the medical field, particularly in the detection and diagnosis of skin cancer. Convolutional Neural Networks (CNNs), a type of deep learning model, have proven to be exceptionally effective in analyzing medical images and identifying patterns that may indicate the presence of skin cancer.

<br>

### Skin Lesion Categories

The dataset includes the following seven types of skin lesions:
1. Melanocytic nevi (`nv`)
2. Melanoma (`mel`)
3. Benign keratosis-like lesions (`bkl`)
4. Basal cell carcinoma (`bcc`)
5. Actinic keratoses (`akiec`)
6. Vascular lesions (`vasc`)
7. Dermatofibroma (`df`)

<br>

### Dataset Attributes

Below is a description of the key attributes (columns) included in the dataset:

| **Attribute**  | **Description**                                                                 |
|----------------|---------------------------------------------------------------------------------|
| `lesion_id`    | Unique identifier for each lesion                                               |
| `image_id`     | Unique identifier for each image                                                |
| `dx`           | Diagnosis label for the lesion (e.g., `mel`, `vasc`, `bcc`, etc.)         |
| `dx_type`      | Type of diagnosis, such as `histo` (histopathology), `follow_up`, `consensus`, or `confocal` |
| `age`          | Age of the patient at the time of image acquisition                             |
| `sex`          | Gender of the patient (`male` or `female`)                                      |
| `localization` | Localization of the lesion on the body (e.g., `back`, `lower extremity`, etc.)  |

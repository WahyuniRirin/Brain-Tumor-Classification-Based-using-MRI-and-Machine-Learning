# Brain Tumor Classification using MRI with Machine Learning

This repository contains a machine learning project that focuses on classifying brain tumors from MRI scans into four distinct categories: Glioma Tumor, Meningioma Tumor, Pituitary Tumor, and No Tumor. The model leverages deep learning techniques to accurately identify and classify tumor types based on MRI imaging data, providing a valuable tool for medical diagnostics and research.

## 🧠 Brains Tumor: An Overview
A brain tumor is an abnormal growth of cells within the brain that can be either benign (non-cancerous) or malignant (cancerous). These tumors can originate from the brain tissue itself, which are known as primary brain tumors, or they can spread to the brain from other parts of the body, referred to as secondary brain tumors or metastases.

### Types of Brain Tumors:

1. Meningioma
- Definition: Meningiomas are the most common type of primary brain tumor. They originate from the meninges, which are the protective layers surrounding the brain and spinal cord.

- Characteristics:
Generally benign (non-cancerous) and slow-growing.
Accounts for about 30-40% of all brain tumors.
More common in older adults and particularly in women.

- Symptoms: Often asymptomatic for years. When symptoms appear, they may include headaches, seizures, or neurological deficits depending on the tumor's location.

- Treatment: Surgical removal is often the preferred treatment, especially if the tumor is accessible. Radiation therapy may be used if surgery is not possible.

2. Glioma
- Definition: Gliomas are a category of brain tumors that arise from glial cells, which support and protect neurons in the brain.
- Subtypes:
	- Astrocytoma: Originates from astrocytes (a type of glial cell).
	- Oligodendroglioma: Develops from oligodendrocytes, which produce myelin (a protective layer around nerve fibers).
	- Ependymoma: Arises from cells lining the ventricles of the brain and spinal cord.

- Grades: Gliomas can range from low-grade (benign) to high-grade (malignant).
	- Glioblastoma multiforme (GBM) is the most aggressive form, with poor prognosis.

- Symptoms: Depend on the tumor's location but may include headaches, seizures, memory issues, and changes in personality.

- Treatment: Typically involves a combination of surgery, radiation therapy, and chemotherapy. Targeted therapies and immunotherapies are emerging treatment options, especially for aggressive gliomas like GBM.

3. Pituitary Tumors

- Definition: These tumors develop in the pituitary gland, a small hormone-producing gland at the base of the brain. They are also known as pituitary adenomas.

- Characteristics:
Usually benign and slow-growing.
Can be functional (hormone-producing) or non-functional (do not produce hormones).

- Symptoms:
	- Hormonal Imbalance: Functional pituitary tumors can cause conditions like Cushing's disease, hyperthyroidism, or acromegaly due to excess hormone production.
	- Compression Symptoms: Large tumors can press on nearby structures, leading to headaches, vision problems, or other neurological issues.
Treatment: Options include surgical removal, especially for larger tumors, medication to manage hormone levels, and radiation therapy for residual tumor growth.

4. Metastatic (Secondary) Brain Tumors

- Definition: These tumors are cancerous growths that have spread (metastasized) to the brain from other parts of the body. They are the most common type of brain tumors in adults.

- Common Primary Sources:
	- Lung cancer (most common source)
	- Breast cancer
	- Melanoma (skin cancer)
	- Kidney cancer
	- Colon cancer

- Symptoms: Depend on the number, size, and location of the metastases, but may include headaches, seizures, cognitive impairments, and focal neurological deficits.

- Treatment:
	- Surgery: May be an option if there are a limited number of accessible brain metastases.
	- Radiation Therapy:
		- Whole Brain Radiation Therapy (WBRT): For multiple metastases.
		- Stereotactic Radiosurgery (SRS): A precise form of radiation for smaller, localized tumors.
		- Targeted Therapy and Immunotherapy: Used depending on the type of primary cancer.


## 🔍 Project Overview 
This project uses MRI scans, which are widely used in medical imaging due to their high resolution and clarity, especially for soft tissue differentiation. The solution employs a **Convolutional Neural Network (CNN)** to classify MRI images. The deep learning model is trained on a dataset consisting of brain MRI images labeled into four categories. The goal is to build an automated system that can assist healthcare professionals in the early diagnosis of brain tumors, potentially improving patient outcomes.

## 📁 Dataset
The dataset used in this project is organized into Training and Testing folders, each containing subfolders for the four categories:
- glioma_tumor/
- meningioma_tumor/
- no_tumor/
- pituitary_tumor/

Each subfolder contains MRI images that serve as input for training and evaluating the model. The images are preprocessed to ensure uniformity in size (150x150 pixels) and normalized for better performance during training.




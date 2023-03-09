# BreastCancerClassification

This Dataset is taken from:
https://www.kaggle.com/competitions/rsna-breast-cancer-detection/data.

The Dataset contains radiographic breast images of female subjects.

Files are mammograms, in dicom format. There are usually but not always 4 images per patient. Note that many of the images use the jpeg 2000 format which may you may need special libraries to load.

The metadata contains the following features:

# site_id - ID code for the source hospital.
# patient_id - ID code for the patient.
# image_id - ID code for the image.
# laterality - Whether the image is of the left or right breast.
# view - The orientation of the image. The default for a screening exam is to capture two views per breast.
# age - The patient's age in years.
# implant - Whether or not the patient had breast implants. Site 1 only provides breast implant information at    the patient level, not at the breast level.
# density - A rating for how dense the breast tissue is, with A being the least dense and D being the most        dense. Extremely dense tissue can make diagnosis more difficult. Only provided for train.
# machine_id - An ID code for the imaging device.
# cancer - Whether or not the breast was positive for malignant cancer. The target value. Only provided for      train.
# biopsy - Whether or not a follow-up biopsy was performed on the breast. Only provided for train.
# invasive - If the breast is positive for cancer, whether or not the cancer proved to be invasive. Only          provided for train.
# BIRADS - 0 if the breast required follow-up, 1 if the breast was rated as negative for cancer, and 2 if the    breast was rated as normal. Only provided for train.
# prediction_id - The ID for the matching submission row. Multiple images will share the same prediction ID.      Test only.
# difficult_negative_case - True if the case was unusually difficult. Only provided for train.


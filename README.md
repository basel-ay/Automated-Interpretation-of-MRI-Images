# Automated Interpretation of MRI Images

## Analyze Knee MRIs with Python 🚑

In this project, we will specifically focus on Anterior Cruciate Ligament (ACL) tears which are the most common knee injuries among top athletes in soccer or basketball.

ACL tears happen when the anterior cruciate ligament is either stretched, partially torn, or completely torn. The most common injury is a complete tear.

Symptoms include pain, a popping sound during injury, instability of the knee, and joint swelling, There are around 200,000 ACL tears each year in the United States, with over 100,000 ACL reconstruction surgeries per year.

<p align="center">
  <img src="https://user-images.githubusercontent.com/64821137/194508556-42020b09-0b4d-4fab-bda0-602050ccd514.png" />
</p>

## Magnetic Resonance Imaging

Magnetic Resonance Imaging (MRI) is a medical imaging technique used in radiology to form a picture of the anatomy and the physiological processes of the body.

MRI is used to diagnose how well you responded to treatment as well as detecting tears and structural problems such as heart attacks, brain injury, blood vessel damage, etc.

<p align="center">
  <img src="https://user-images.githubusercontent.com/64821137/194508603-d738b7ff-6bdd-415d-9eff-e74274631653.png" />
</p>

MRNet dataset
MRNet is a knee MRI dataset provided by Andrew Ng’s Stanford lab.

It’s split in training set (1130 cases), validation set (120 cases) and test set (120 cases) and is organized as follows:

<p align="center">
  <img src="https://user-images.githubusercontent.com/64821137/194508660-da07bb92-34f6-4009-ba57-441628a4b715.png" />
</p>

Each case, in both train and valid folder, has 3 MRI scans taken from different planes: sagittal, coronal and axial.

To make a proper decision regarding a case, the radiologist usually looks at MRI scans from different planes to have a global view.

<p align="center">
  <img src="https://user-images.githubusercontent.com/64821137/194508687-5390884d-746c-4a9b-a76c-1bee335d9d54.png" />
</p>

## Automated Interpretation

<p align="center">
  <img src="https://user-images.githubusercontent.com/64821137/194510072-6157153c-2611-41d4-9f7b-f5181474460a.png" />
</p>

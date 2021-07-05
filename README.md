# Brain MRI Generation using GAN
Misdiagnosis in the medical field is a very serious issue but it’s also uncomfortably common to occur. Imaging procedures in the medical field requires an expert radiologist’s opinion since interpreting them is not a simple binary process ( Normal or Abnormal). Even so, one radiologist may see something that another does not. This can lead to conflicting reports and make it difficult to effectively recommend treatment options to the patient.

One of the complicated tasks in medical imaging is to diagnose MRI(Magnetic Resonance Imaging). Sometimes to interpret the scan, the radiologist needs different variations of the imaging which can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding.

But to have access to different imaging is difficult & expensive. With the help of deep learning, we can use style transfer to generate artificial MRI images of different contrast levels from existing MRI scans. This will help to provide a better diagnosis with the help of an additional image.

In this project we will use CycleGAN to translate the style of one MRI image to another, which will help in better understanding of the scanned image. Using GANs you will create T2 weighted images from T1 weighted MRI image and vice-versa.
We will build Generative adversarial model which can generate artificial MRI images of different contrast levels from existing MRI scans.

Data can be found here https://drive.google.com/file/d/1F_ySoMXuKEQE0aYAvdNDXQPlGobs1OSP/view?usp=sharing

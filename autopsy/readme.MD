# Autopsy

### Autopsy is a complete open-source digital forensics platform that enables digital security and forensic professionals to conduct detailed analysis of computer systems and efficiently recover data. It supports a wide range of file formats and file systems, and features an intuitive graphical interface that makes navigating recovered data easy. Additionally, it comes equipped with numerous built-in forensic analysis tools, including data recovery, registry analysis, memory analysis, among others. Autopsy is a powerful tool that is used worldwide for conducting digital investigations and analyzing security incidents.

---

## we create an image of our attacked computer

### inside our attacked computer we execute the following command and select our affected partition

    sudo fdisk -l
    
  

<img src="https://user-images.githubusercontent.com/131694378/235357455-3138ab2d-b0b9-4821-b07b-a351f3b1bf16.png" width="600" height="350">

### we create the imagen

        sudo dd if=/dev/sdb of=/route/of/the/image.img bs=4M
        
### now we create a virtual machine with kalilinux and we take the image there

<img src="https://user-images.githubusercontent.com/131694378/235358942-921e1b95-d3ba-4bfe-a6d4-7ecac6e07461.png" width="600" height="350">

### open autopsy in applications and open the link in a browser http://localhost:9999/autopsy

<img src="https://user-images.githubusercontent.com/131694378/235366709-42591888-3174-48c3-a741-ac3d13459a2b.png" width="600" height="350">

### within the application we add a new case and complete the fields, then add the image

<img src="https://user-images.githubusercontent.com/131694378/235366664-f55c5564-a593-47a8-86e7-3b7614fb1245.png" width="600" height="350">

### select the newly created file of type ext and then click analyze

<img src="https://user-images.githubusercontent.com/131694378/235367027-b60fa5a6-de39-4e7c-8396-ebd5d3ee9981.png" width="600" height="350">

### Here we can analyze the files on the disk, records, history, etc.

<img src="https://user-images.githubusercontent.com/131694378/235367193-b4bcd2f2-8b6e-4c7c-8ff4-42ac5975eb8b.png" width="600" height="350">






# Tensorflow Plant disease classifier

This is the repository developed for 'Image Classifier in TensorFlow [CodeLab](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/?utm_campaign=chrome_series_machinelearning_063016&utm_source=gdev&utm_medium=yt-desc#0) by Google as a guide. 

Scientists can use this classifier to automatically label 38 disease in 13 plants.
Looking for images in '1. Rice blast'
Looking for images in '10. Barley yellow dwarf virus in oats'
Looking for images in '11. Loose smut of wheat'
Looking for images in '12. Sooty head molds of wheat'
Looking for images in '13. Common root rot in wheat'
Looking for images in '14. Sclerotinia Blight of Chickpea'
Looking for images in '16. Botrytis Grey Mold of Chickpea'
Looking for images in '17. Crown Rot of peanut'
Looking for images in '18. Early and Late leaf Spots in peanut'
Looking for images in '19. Bud Necrosis Virus in peanut'
Looking for images in '2. Narrow Brown Spot of rice'
Looking for images in '20. Anthracnose Fruit Rot in Tomato'
Looking for images in '21. Early Blight in tomato'
Looking for images in '22 Cercospora leaf spot  in peppers'
Looking for images in '23. Southern Blight in peppers'
Looking for images in '24. Phyllody disease in peppers'
Looking for images in '25.Basal wilt in peppers'
Looking for images in '26. Soybean Rust'
Looking for images in '27. Bacterial Pustule in soybean'
Looking for images in '28. Downy Mildew in Soybean'
Looking for images in '29. Frogeye Leaf Spot in Soybean'
Looking for images in '3. Bacterial kernel blight(barley)'
Looking for images in '30. Soybean Mosaic Virus in Soybean'
Looking for images in '31. Peacock spot in olives'
Looking for images in '32.Anthracnose in olives'
Looking for images in '33. Xylella fastidiosa bacteria in olives'
Looking for images in '34. Pink eye in potatoes'
WARNING: Folder has less than 20 images, which may cause issues.
Looking for images in '36. Colletotrichum Leaf spot and blight in neem'
Looking for images in '37. Pseudocercospora Leaf spot in neem'
Looking for images in '38. fusarium wilt disease in tulsi'
Looking for images in '39. Basil Shoot Blight in tulsi'
Looking for images in '4. leaf rust barley'
Looking for images in '40. Downy Mildew in tulsi'
Looking for images in '5. Net blotch (barley)'
Looking for images in '6.Powdery Mildew(barley)'
Looking for images in '7. Covered smut (Ustilago hordei) Barley'
Looking for images in '8. Septoria avenae blotch in Oats'
Looking for images in '9. stem rust in oats'



##Requirements

* [docker](https://www.docker.com/products/docker-toolbox)

##Usage 

1. Start the docker image `docker run -it -v docker run -it --volume ~/plant_disease/:/plant_disease --workdir /plant_disease  tensorflow/tensorflow:1.1.0 bash
`

2. Run the label_image script to label the image. `python /plant_disease/label_image.py  <path_to_file>`


# Plant_disease_TensorFlow_classification

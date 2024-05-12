First I filtered out Moulvibazar sadar upazila from administrative border shape file. Then from lansat 9 imagery I filtered by date('2022-01-01', '2022-12-31'), upazila boundary and cloud cover. After that called a function to calculate NDVI for every image in the filterd out landsat 9 imagery. Then we call a image from the new collection of image and visualize it in new layer.

[NDVI Moulvibazar Sadar Upazila Image](https://github.com/AtikulRahi/ndviUpazila/blob/main/NDVIupazila.JPG)

[NDVI Moulvibazar Sadar Upazila Code](https://github.com/AtikulRahi/ndviUpazila/blob/main/ndviUpazila.js)

[NDVI Moulvibazar Sadar Upazila GEE Code link](https://code.earthengine.google.com/c2b210511e3c070b539ffb1ebb6b367f)


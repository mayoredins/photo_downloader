
# Automatic Photo Download and Sorting
This repository contains two Python scripts that enable automatic photo downloading from Google based on a search keyword and automatic sorting of photos into folders based on their content.

## Code 1: Automatic Photo Download from Google
Overview
The first code (google_photo_downloader.py) utilizes the google_images_search library to search and download photos from Google based on a specified keyword.

Instructions
Install the required libraries by running pip install google_images_search.
Obtain the necessary API key and CX by creating a project on the Google Developers Console and enabling the Google Custom Search API.
Open the google_photo_downloader.py file and replace 'your_api_key' and 'your_cx' with your own API key and CX.
Set the desired search keyword and the number of images to download.
Run the script (python google_photo_downloader.py).
The downloaded images will be saved to the specified directory.
## Code 2: Automatic Photo Sorting
Overview
The second code (photo_sorter.py) uses image recognition and clustering techniques to automatically sort photos into folders based on their content.

### Instructions
Ensure that you have the OpenCV and scikit-learn libraries installed (pip install opencv-python scikit-learn).
Place the photos you want to sort in a directory.
Open the photo_sorter.py file and set the photos_directory variable to the path of the directory containing the photos.
Adjust the num_clusters variable to the desired number of clusters (folders) for sorting.
Run the script (python photo_sorter.py).
The script will analyze the photos, create folders for each cluster, and move the images to their respective folders based on their content.
Please note that the second code focuses on sorting images based on visual similarity and does not involve actual image content summarization. For more accurate summarization, advanced techniques like image captioning or natural language processing with image recognition would be required.

## Warnings
Please ensure that you comply with Google's terms and conditions and any applicable legal restrictions when using the Google photo download code.

Enjoy automatically downloading and sorting your photos!





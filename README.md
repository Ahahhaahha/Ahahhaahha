
from PIL import Image



# Load the images to analyze them

image1_path = '/mnt/data/file-6d8Sx1HUoj5ZQJugL9GdmrOQ'

image2_path = '/mnt/data/file-WqT0BGtDSAc7c5df204Yb9C9'



# Open the images

image1 = Image.open(image1_path)

image2 = Image.open(image2_path)



# Display the images for review

image1.show()

image2.show()

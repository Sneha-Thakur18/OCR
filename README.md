from PIL import Image
img = Image.open('1.jpg').convert('L')  # convert image to 8-bit grayscale
WIDTH, HEIGHT = img.size
data = list(img.getdata())  # convert image data to a list of integers
# Convert the 2D data to a 1D array
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)

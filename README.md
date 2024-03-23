from PIL import Image
img = Image.open('1.jpg').convert('L')  # convert image to 8-bit grayscale
WIDTH, HEIGHT = img.size
data = list(img.getdata())  # convert image data to a list of integers
# Convert the 2D data to a 1D array
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('2.jpg').convert('L')
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('3.jpg').convert('L')
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('4.jpg').convert('L')
WIDTH, HEIGHT = img.size
data = list(img.getdata())  
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('5.jpg').convert('L') 
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('01.jpg').convert('L') 
WIDTH, HEIGHT = img.size
data = list(img.getdata())  
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('02.jpg').convert('L')
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('03.jpg').convert('L')  
WIDTH, HEIGHT = img.size
data = list(img.getdata())
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('04.jpg').convert('L')
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('05.jpg').convert('L')  
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('06.jpg').convert('L') 
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('07.jpg').convert('L') 
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)


from PIL import Image
img = Image.open('08.jpg').convert('L') 
WIDTH, HEIGHT = img.size
data = list(img.getdata()) 
data_1d = [data[row * WIDTH + col] for col in range(WIDTH) for row in range(HEIGHT)]
print(data_1d)

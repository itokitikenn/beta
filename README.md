from PIL import Image, ImageDraw

im = Image.new('RGB', (500, 300), (128, 128, 128))
draw = ImageDraw.Draw(im)        # beta

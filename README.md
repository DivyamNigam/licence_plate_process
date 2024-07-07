# licence_plate_process
A ML project to process a license plate using pytorch YOLO and easy OCR.
YOLO V8 Licene plate Model- https://github.com/computervisioneng/yolo-license-plate-detection

This project is very beginner-friendly and made for People starting in ML, So outlook is:

1. We Start from the raw image, using YOLO v8 pre-trained custom model for analyzing license plates. We locate the license plate.
2. Then We take that processed image and crop it out so we get only the license plate part.
3. Then using easy ocr we extract the text from the image.
4. Last is we take output of the final image with license plate and text and extract the text into a csv.

5. Some pointers EASY OCR might not work when running code on local machine as some laptops can't handel it (my can't) , but running on GPU Runtime on Collab will work.

I also have a version of code that can take live input from a webcam. It is only 4 lines of extra code.
6. I hope it is simple enough for beginners

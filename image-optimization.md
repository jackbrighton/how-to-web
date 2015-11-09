#Website Performance: Images

Images on the web are important to telling stories and connecting with your audience. If the images aren’t optimized, they can also weigh down your web pages and make them slow to load. 

##What is Image Optimization

Image optimization involves compressing the file size of image using a tool like Adobe Photoshop. We want the highest quality image with the smallest possible file size. Too much compression can impair the quality of the image. Too little compression can result in a large image file size which slows the performance of our web page. Optimization is finding the right balance between quality and file size.

Consider these two images:

![image of Fragile Arch]
(img/arches-1200px.jpg)
Width: 1200px
Height: 800px
File Size: 939 Kilobytes

![image of Fragile Arch]
(img/arches-1200px-web.jpg)
Width: 1200px
Height: 800px
File Size: 110 Kilobytes

The second image has a file size of less than 12 percent of the first. You can probably see a slight degradation in the image quality. But most people would not notice the difference between these two on a web page. 

On the web we should not use any image with a file size of 939 Kilobytes. This will slow the loading of the page, especially on slower connections and mobile devices. We want to keep website images under 100 KB if we can, and much lower for smaller images. For example, here’s the same image reduced in dimensions:

![image of Fragile Arch]
(img/arches-300px.jpg)
Width: 300px
Height: 200px
File Size: 192 Kilobytes

![image of Fragile Arch]
(img/arches-300px-web.jpg)
Width: 300px
Height: 200px
File Size: 14 Kilobytes

##How to Optimize Images in Photoshop

Best practice for optimization is to start with the highest-quality source image, then resize and compress it for the web. Start by cropping and resizing the image for the space it will fill on your web page. If the image will be displayed in a sidebar widget that’s 300px wide, there’s no reason to upload an image wider than 300px for that space. Reducing the size of the image by itself will reduce its file size.

After the image is cropped and sized, in the File menu select Save for Web:

![Save for Web dialogue box in Photoshop]
(img/save-for-web.png)

Here you can select which image format to export (always use JPEG for photos), and how much compression to apply. Medium is often the optimum setting, but this is a judgement call. If you don’t see a preview of both the Original image and the JPEG export, click the 2-up tab at the top. Now you can try different compression settings and see a preview of the results, including the file size:

![Closer view of Save for Web dialogue box in Photoshop]
(img/save-for-web-2.png)

Here’s a video from Lynda.com that explains [how to use this feature of Photoshop](https://youtu.be/OL0DwX7dnto).

Here’s another really good [tutorial on Photoshop’s Save For Web](http://photography.tutsplus.com/tutorials/save-for-web-better-jpeg-compression-with-adobe-photoshop--cms-23080) that walks through the process. 

##Optimizing Images without Photoshop

If you don’t use Photoshop, there are any number of other tools for optimizing website images. 

Compressor.io is a free online tool. You can drag and drop a source image into it, and download a compressed version of the image. Compressor.io doesn’t have any cropping or resizing tools, and you can’t adjust the amount of compression. In our tests, Photoshop does a better job of balancing image quality and file size. But if you have an image sized correctly for your website, it’ll do in a pinch: [https://compressor.io/](https://compressor.io/)

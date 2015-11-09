#Website Performance: Photos

Photos on the web are important to telling stories and connecting with your audience. If the photos aren’t optimized, they can also weigh down your web pages and make them slow to load. To improve the performance of your website, photo optimization is often the best place to start.

##What is Photo Optimization

Photo optimization involves compressing the file size of photo using a tool like Adobe Photoshop. We want the highest quality photo with the smallest possible file size. Too much compression can impair the quality of the image. Too little compression can result in a large photo file size which slows the performance of our web page. Optimization is finding the right balance between quality and file size.

Consider these two images:

![photo of Fragile Arch]
(img/arches-1200px.jpg)
**Not Optimized. Width: 1200px, Height: 800px, File Size: 939 Kilobytes**

![photo of Fragile Arch]
(img/arches-1200px-web.jpg)
**Optimized. Width: 1200px, Height: 800px, File Size: 107 Kilobytes**

The second photo has a file size of less than 12 percent of the first. You can probably see a slight degradation in the photo quality. But most people would not notice the difference between these two on a web page. 

On the web we should never use any photo with a file size like 939 Kilobytes. This will slow the loading of the page, especially on slower connections and mobile devices. We want to keep website photos under 100 KB if we can, and much lower for smaller images. For example, here’s the same photo reduced in dimensions:

![photo of Fragile Arch]
(img/arches-300px.jpg)
**Not Optimized. Width: 300px, Height: 200px, File Size: 192 Kilobytes**

![photo of Fragile Arch]
(img/arches-300px-web.jpg)
**Optimized. Width: 300px, Height: 200px, File Size: 14 Kilobytes**

The file size of the second photo is less that 10 percent of the first image, yet most people would see no difference in photo quality. If you have a web page displaying a number of similar-sized images, for example a gallery page or a series of stories with thumbnail images, smaller photo file sizes can add up a huge reduction in page loading time.

##How to Optimize Photos in Photoshop

Best practice for optimization is to start with the highest-quality source photo, then resize and compress it for the web. Start by cropping and resizing the photo for the space it will fill on your web page. If the photo will be displayed in a sidebar widget that’s 300px wide, there’s no reason to upload a photo wider than 300px for that space. Reducing the size of the photo by itself will reduce its file size.

After the photo is cropped and sized, in the File menu go to Export -> Save for Web:

![Save for Web dialogue box in Photoshop]
(img/save-for-web.png)

Here you can select which photo format to export (always use JPEG for photos), and how much compression to apply. Medium is often the optimum setting, but this is a judgement call. If you don’t see a preview of both the Original photo and the JPEG export, click the 2-Up tab at the top. Now you can try different compression settings and see a preview of the results, including the file size:

![Closer view of Save for Web dialogue box in Photoshop]
(img/save-for-web-2.png)

Once you're happy with the image quality and file size reduction, click Save to create your web-optimized photo. This will not affect your original image, which should be archived for possible use in the future.

###More Tutorials on Photoshop's Save for Web

Here’s a video from Lynda.com that explains [how to use Save for Web in Photoshop](https://youtu.be/OL0DwX7dnto).

Here’s another really good [tutorial on Photoshop’s Save For Web](http://photography.tutsplus.com/tutorials/save-for-web-better-jpeg-compression-with-adobe-photoshop--cms-23080) that walks through the process. 

Tip: If you like keyboard shortcuts, in Photoshop you can launch Save for Web like this:
- Command + Shift + Option + s (Mac)
- Control + Shift + Alt + s (Windows)

##Optimizing Photos without Photoshop

If you don’t use Photoshop, there are any number of other tools for optimizing website images. 

Compressor.io is a free online tool. You can drag and drop a source photo into it, and download a compressed version of the image. Compressor.io doesn’t have any cropping or resizing tools, and you can’t adjust the amount of compression. In our tests, Photoshop does a better job of balancing photo quality and file size. But if you have a photo sized correctly for your website, it’ll do in a pinch: [https://compressor.io/](https://compressor.io/)

##Your Photo Workflow

If you've produced photos for print, you know it's important to maintain the highest quality photo throughout the process. But with today's cameras, the highest quality photo is likely to be 5000 pixels wide, and more than 20 Megabytes in file size. Such a photo is great for print, but a problem on the web. 

Best practice is to safely store the original photo files in their highest resolution, for the day when you need to resize or reuse them in another context. Use the original photos to crop, size, and export for the web, then keep the originals safe for future use.

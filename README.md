<h1>Hybrid-image</h1>
<p>The project of creating Hybrid-image implement the paper[1]. The Hybrid images, a technique that produces static images with two interpretations, which change as a function of viewing distance.</p>
<p>During the implementation, to get the Hybrid-image, all operation on image are defined in frequence domain by using Fourier Transform[2]. The techinique of low pass fitler and high pass filter are also required. There are two kinds of filter are implemented to low pass and high pass in this preject, the Gaussian filter and idea fitler</p>
<p>The image convolution with high pass fitler remains the high freqency components(the details). Otherwise the low pass filter, the image keep the low frequence componments(rough structure). So we can create the Hybrid-image by combining these two images after both of them passed through the different fitlers</p>

<h2>Running the demo</h2>
<p>The result of Hybrid-image</p>
<p>In the close distance, you can see a cat. For the far distance, it's a dog</p>
<img src="result_hybrid_image/3_cat%20and%203_dog.jpg">
<p>Einstein and marilyn</p>
<img src="result_hybrid_image/4_einstein%20and%204_marilyn.jpg">

<h2>References</h2>
<p>[1] Aude Oliva, Antonio Torralba, Philippe G Schyns, <I>Hybrid images</I>, July 2006</p>
<p>[2] jserv, "圖解傅立葉分析", from <a href="https://hackmd.io/@sysprog/fourier-transform">https://hackmd.io/@sysprog/fourier-transform</a></p>
<p>[3] j2kun, "Making Hybrid Images", from <a href="https://jeremykun.com/2014/09/29/hybrid-images/">https://jeremykun.com/2014/09/29/hybrid-images/</a></p>



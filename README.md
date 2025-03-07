# TIP2022-BGDC-A Unified Pansharpening Model Based on Band-Adaptive Gradient and Detail Correction

Paper link: https://ieeexplore.ieee.org/document/9664491

For reduced scale experiments (simulation), please run main_RS.m, for full scale (real) experiments, please run main_FS.m.

If you wish to cite this paper, please refer to:  

    @article{lu_unified_2022,
	title = {A Unified Pansharpening Model Based on Band-Adaptive Gradient and Detail Correction},
	volume = {31},
	issn = {1057-7149, 1941-0042},
	url = {https://ieeexplore.ieee.org/document/9664491/},
	doi = {10.1109/TIP.2021.3137020},
	abstract = {Pansharpening is used to fuse a panchromatic ({PAN}) image with a multispectral ({MS}) image to obtain a highspatial-resolution multispectral ({HRMS}) image. Traditional pansharpening methods face difﬁculties in obtaining accurate details and have low computational efﬁciency. In this study, a uniﬁed pansharpening model based on the band-adaptive gradient and detail correction is proposed. First, a spectral ﬁdelity constraint is designed by keeping each band of the {HRMS} image consistent with that of the {MS} image. Then, a band-adaptive gradient correction model is constructed by exploring the gradient relationship between a {PAN} image and each band of the {MS} image, so as to adaptively obtain an accurate spatial structure for the estimated {HRMS} image. To reﬁne the spatial details, a detail correction constraint is deﬁned based on the parameter transfer by designing a reduced-scale parameter acquisition model. Finally, a uniﬁed model is constructed based on the gradient and detail corrections, which is then solved by an alternating direction multiplier method. Both reduced-scale and full-scale experiments are conducted on several datasets. Compared with state-of-theart pansharpening methods, the proposed method can achieve the best results in terms of fusion quality and has high efﬁciency. Speciﬁcally, our method improves the {SAM} and {ERGAS} metrics by 17.6\% and 21.2\% respectively compared to the traditional approach with the best average values, and improves these two metrics by 4.3\% and 10.3\% respectively compared to the learning-based approach with the best average values.},
	pages = {918--933},
	journaltitle = {{IEEE} Transactions on Image Processing},
	shortjournal = {{IEEE} Trans. on Image Process.},
	author = {Lu, Hangyuan and Yang, Yong and Huang, Shuying and Tu, Wei and Wan, Weiguo},
	urldate = {2022-01-15},
	date = {2022},
	langid = {english},	
    }

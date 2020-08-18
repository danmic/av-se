# Deep-Learning-Based Audio-Visual Speech Enhancement and Separation

This document provides a list of resources on audio-visual speech enhancement and separation based on deep learning. It can be seen as an appendix to [the overview paper that we recently wrote]().

Our intention is to update the list, when new material on the topic is released. Feel free to propose changes or point out a resource that should be included.

If you like and use this work, please :star: and consider citing our overview article. This will highlight the interest of the community on our work.

    @inproceedings{-,
	Author = {-},
	Title = {-},
	Booktitle  = {-},
	Year = {-}
    }


## Table of Contents  
- [Audio-Visual Speech Corpora](#audio-visual-speech-corpora)
- [Performance Assessment](#performance-assessment)
- [Audio-Visual Speech Enhancement and Separation](#audio-visual-speech-enhancement-and-separation)
- [Speech Reconstruction from Silent Videos](#speech-reconstruction-from-silent-videos)
- [Audio-Visual Sound Source Separation for Non-Speech Signals](#audio-visual-sound-source-separation-for-non-speech-signals)
- [Related Overview Articles](#related-overview-articles)


## Audio-Visual Speech Corpora

* AVA-ActiveSpeaker [[paper]](https://arxiv.org/pdf/1901.01342.pdf) [[dataset page]](https://research.google.com/ava/index.html)

* AV Chinese Mandarin [[paper]](https://arxiv.org/pdf/1909.07352.pdf)

* AVSpeech [[paper]](https://arxiv.org/pdf/1804.03619.pdf) [[dataset page]](https://looking-to-listen.github.io/avspeech/index.html)

* ASPIRE [[paper]](https://arxiv.org/pdf/1909.10407.pdf) [[dataset page]](https://cochleanet.github.io)

* CUAVE [[paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.91.6375&rep=rep1&type=pdf)

* GRID [[paper]](http://www.laslab.org/wp-content/uploads/an_audio-visual_corpus_for_speech_perception_and_automatic_speech_recognition.pdf) [[dataset page]](http://spandh.dcs.shef.ac.uk/gridcorpus/)

* KinectDigits [[paper]](https://www.honda-ri.de/pubs/pdf/3275.pdf) [[dataset page]](https://zenodo.org/record/823531#.Xzml9y17HOQ)

* LDC2009V01 [[dataset page]](https://catalog.ldc.upenn.edu/LDC2009V01)

* Lombard GRID [[paper]](https://staffwww.dcs.shef.ac.uk/people/G.Brown/pdf/alghamdi_etal_2018_lombard.pdf) [[dataset page]](http://spandh.dcs.shef.ac.uk/avlombard/)

* LRS [[paper]](http://www.robots.ox.ac.uk/~vgg/publications/2017/Chung17/chung17.pdf)

* LRS2 [[paper]](https://www.robots.ox.ac.uk/~vgg/publications/2019/Afouras19/afouras18c.pdf) [[dataset page]](http://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html)

* LRS3 [[paper]](https://arxiv.org/pdf/1809.00496.pdf) [[dataset page]](http://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs3.html)

* LRW [[paper]](https://ora.ox.ac.uk/objects/uuid:c3238375-ec8b-4ecd-9543-8b179a6b74ba/download_file?safe_filename=chung16.pdf&file_format=application%2Fpdf&type_of_work=Conference+item) [[dataset page]](http://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html)

* Mandarin Sentences Corpus [[paper]](https://arxiv.org/pdf/1703.10893)

* MODALITY [[paper]](https://link.springer.com/article/10.1007/s10844-016-0438-z) [[dataset page]](http://modality-corpus.org)

* MV-LRS [[paper]](https://ora.ox.ac.uk/objects/uuid:9f06858c-349c-416f-8ace-87751cd401fc/download_file?safe_filename=chung17a.pdf&file_format=application%2Fpdf&type_of_work=Conference+item)

* NTCD-TIMIT [[paper]](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/0860.PDF) [[dataset page]](https://zenodo.org/record/260228#.XzqK5y17HOQ)

* Obama Weekly Addresses [[dataset page]](https://arxiv.org/pdf/1711.08789)

* OuluVS [[paper]](http://www.ee.oulu.fi/~gyzhao/Papers/2009/Lipreading%20with%20Local%20Spatiotemporal.pdf) [[dataset page]](https://www.oulu.fi/cmvs/node/41315)

* OuluVS2 [[paper]](https://www.researchgate.net/profile/Ziheng_Zhou/publication/283593688_OuluVS2_A_multi-view_audiovisual_database_for_non-rigid_mouth_motion_analysis/links/5754caf608ae17e65ecccde3.pdf) [[dataset page]](http://www.ee.oulu.fi/research/imag/OuluVS2/)

* RAVDESS [[paper]](https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0196391&type=printable) [[dataset page]](https://zenodo.org/record/1188976#.XzskXy17HOQ)

* Small Mandarin Sentences Corpus [[paper]](https://www.citi.sinica.edu.tw/papers/yu.tsao/5427-F.pdf)

* TCD-TIMIT [[paper]](https://ieeexplore.ieee.org/abstract/document/7050271) [[dataset page]](https://sigmedia.tcd.ie/TCDTIMIT/)

* VoxCeleb [[paper]](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html) [[dataset page]](https://arxiv.org/pdf/1706.08612)

* VoxCeleb2 [[paper]](https://arxiv.org/pdf/1806.05622) [[dataset page]](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)


## Performance Assessment

### Estimators of speech quality based on perceptual models 

* CSIG / CBAK / COVRL [[paper]](https://ecs.utdallas.edu/loizou/speech/obj_paper_jan08.pdf) [[unofficial code]](https://github.com/nanahou/Awesome-Speech-Enhancement/tree/master/tools)

* HASQI [[paper v1]](https://www.aes.org/e-lib/browse.cfm?elib=15451) [[paper v2]](https://www.aes.org/e-lib/browse.cfm?elib=17126) [[code]](https://www.colorado.edu/lab/hearlab/resources)

* PESQ [[paper]](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.5.9136&rep=rep1&type=pdf) [[code]](https://www.itu.int/rec/T-REC-P.862-200511-I!Amd2/en)

* POLQA [[recommendation]](https://www.itu.int/rec/T-REC-P.863-201803-I/en) [[code]](http://www.polqa.info/products.html)

* ViSQOL [[paper 1]](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/39979.pdf) [[paper 2]](https://asmp-eurasipjournals.springeropen.com/articles/10.1186/s13636-015-0054-9) [[code]](https://github.com/google/visqol)

### Estimators of speech quality based on energy ratios

* SDR / SIR / SAR (BSS Eval) [[paper]](https://www.irisa.fr/metiss/gribonval/Papers/2006/2006_IEEE_TSAP_VincentFevGrib.pdf) [[code]](http://bass-db.gforge.inria.fr/bss_eval/)

* SDI [[paper]](https://uol.de/f/6/dept/mediphysik/ag/sigproc/download/papers/doclo/journal_wiener.pdf)

* SI-SDR [[paper]](https://arxiv.org/pdf/1811.02508.pdf) [[code]](https://github.com/sigsep/bsseval/issues/3#issuecomment-494995846)

### Estimators of speech intelligibility

* CSII [[paper]](https://www.researchgate.net/profile/James_Kates2/publication/7842209_Coherence_and_the_speech_intelligibility_index/links/546f5dab0cf2d67fc0310f88/Coherence-and-the-speech-intelligibility-index.pdf)

* ESII [[paper]](https://pure.uva.nl/ws/files/3886153/45240_205638y.pdf)

* ESTOI [[paper]](https://www.researchgate.net/profile/Cees_Taal/publication/306046797_An_Algorithm_for_Predicting_the_Intelligibility_of_Speech_Masked_by_Modulated_Noise_Maskers/links/5ae0d5ab0f7e9b2859480a5e/An-Algorithm-for-Predicting-the-Intelligibility-of-Speech-Masked-by-Modulated-Noise-Maskers.pdf) [[code]](http://kom.aau.dk/~jje/code/estoi.m)

* HASPI [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167639314000545) [[code]](https://www.colorado.edu/lab/hearlab/resources)

* SII [[paper]](https://global.ihs.com/doc_detail.cfm?document_name=ANSI%2FASA%20S3%2E5&item_s_key=00009562&csf=ASA) [[code]](http://sii.to/programs.html)

* STOI [[paper]](http://cas.et.tudelft.nl/pubs/Taal2011_1.pdf) [[code]](http://ceestaal.nl/stoi_mp.zip)


## Audio-Visual Speech Enhancement and Separation


## Speech Reconstruction From Silent Videos

* H. Akbari, H. Arora, L. Cao, and N. Mesgarani, “Lip2AudSpec: Speech reconstruction from silent lip movements video,” in Proc. of ICASSP, 2018. [[paper]](https://arxiv.org/pdf/1710.09798.pdf) [[demo 1]](https://www.youtube.com/watch?v=Op7Z9KH5Fis&feature=youtu.be) [[demo 2]](https://www.youtube.com/watch?v=O0Gfb-1lu2k&feature=youtu.be) [[demo 3]](https://github.com/hassanhub/LipReading/tree/master/demo) [[code]](https://github.com/hassanhub/LipReading)

* A. Ephrat, T. Halperin, and S. Peleg, “Improved speech reconstruction from silent video,” in Proc. of CVAVM, 2017. [[paper]](https://arxiv.org/pdf/1708.01204.pdf) [[project page]](http://www.vision.huji.ac.il/vid2speech) [[demo]](https://www.youtube.com/watch?v=Xjbn7h7tpg0&feature=emb_title) 

* A. Ephrat and S. Peleg, “Vid2Speech: Speech reconstruction from silent video,” in Proc. of ICASSP, 2017. [[paper]]() [[project page]](http://www.vision.huji.ac.il/vid2speech/) [[demo 1]](https://www.youtube.com/watch?v=6B0pitNsRSs&feature=emb_title) [[demo 2]](https://www.youtube.com/watch?v=_gG2sewE-IQ&feature=emb_title) [[demo 3]](https://www.youtube.com/watch?v=1FJnv5bf9Mc&feature=emb_title) [[code]](https://github.com/arielephrat/vid2speech)

* Y. Kumar, M. Aggarwal, P. Nawal, S. Satoh, R. R. Shah, and R. Zimmermann, “Harnessing AI for speech reconstruction using multi-view silent video feed,” in Proc. of ACM-MM, 2018. [[paper]](https://arxiv.org/pdf/1807.00619.pdf)

* Y. Kumar, R. Jain, K. M. Salik, R. R. Shah, Y. Yin, and R. Zimmermann, “Lipper: Synthesizing thy speech using multi-view lipreading,” in Proc. of AAAI, 2019. [[paper]](https://arxiv.org/pdf/1907.01367.pdf) [[demo]](https://www.youtube.com/playlist?list=PL9rvax0EIUA4LNaXSeVX5Kt6gu2IBBnsg)

* Y. Kumar, R. Jain, M. Salik, R. R. Shah, R. Zimmermann, and Y. Yin, “MyLipper: A personalized system for speech reconstruction using multi-view visual feeds,” in Proc. of ISM, 2018. [[paper]](https://ieeexplore.ieee.org/document/8603277) [[demo]](https://www.youtube.com/watch?v=aIT0NYbQ0Go&feature=youtu.be)

* T. Le Cornu and B. Milner, “Reconstructing intelligible audio speech from visual speech features,” in Proc. of Interspeech, 2015. [[paper]](https://www.isca-speech.org/archive/interspeech_2015/papers/i15_3355.pdf)

* T. Le Cornu and B. Milner, “Generating intelligible audio speech from visual speech,” IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 25, no. 9, pp. 1751–1761, 2017. [[paper]](https://ueaeprints.uea.ac.uk/id/eprint/64052/1/Accepted_manuscript.pdf) [[demo]](https://www.uea.ac.uk/computing/speech-language-and-audio-processing/v2a-results)

* D. Michelsanti, O. Slizovskaia, G. Haro, E. Go ́mez, Z.-H. Tan, and J. Jensen, “Vocoder-based speech synthesis from silent videos,” in Proc. of Interspeech (to appear), 2020. [[paper]](https://arxiv.org/pdf/2004.02541.pdf) [[project page]](https://danmic.github.io/vid2voc/) [[demo]](https://www.youtube.com/watch?v=dBhBCH-agc4&feature=emb_title)

* K. Prajwal, R. Mukhopadhyay, V. P. Namboodiri, and C. Jawahar, “Learning individual speaking styles for accurate lip to speech synthesis,” in Proc. of CVPR, 2020. [[paper]](https://arxiv.org/pdf/2005.08209.pdf) [[project page]](http://cvit.iiit.ac.in/research/projects/cvit-projects/speaking-by-observing-lip-movements) [[demo]](https://www.youtube.com/watch?v=HziA-jmlk_4&feature=youtu.be) [[code]](https://github.com/Rudrabha/Lip2Wav)

* Y. Takashima, T. Takiguchi, and Y. Ariki, “Exemplar-based lip-to-speech synthesis using convolutional neural networks,” in Proc. of IW-FCV, 2019. [[paper]](http://www.me.cs.scitec.kobe-u.ac.jp/~takigu/pdf/2019/O1-4.pdf)

* S. Uttam, Y. Kumar, D. Sahrawat, M. Aggarwal, R. R. Shah, D. Mahata, and A. Stent, “Hush-hush speak: Speech reconstruction using silent videos,” in Proc. of Interspeech, 2019. [[paper]](https://www.isca-speech.org/archive/Interspeech_2019/pdfs/3269.pdf) [[demo]](https://drive.google.com/open?id=1ZWS4L3SaZyb7SNwTaMpY96uJRYfFcVEG) [[code]](https://github.com/midas-research/hush-hush-speak)

* K. Vougioukas, P. Ma, S. Petridis, and M. Pantic, “Video-driven speech reconstruction using generative adversarial networks,” in Proc. of Interspeech, 2019. [[paper]](https://arxiv.org/pdf/1906.06301.pdf) [[project page]](https://sites.google.com/view/speech-synthesis/home) [[demo 1]](https://www.youtube.com/watch?v=W0IPRd-GeCs&feature=emb_title) [[demo 2]](https://www.youtube.com/watch?v=xl1EmVaCP4s&feature=emb_title) [[demo 3]](https://www.youtube.com/watch?v=KJWCo4lbvAI&feature=emb_title)


## Audio-Visual Sound Source Separation for Non-Speech Signals

* C. Gan, D. Huang, H. Zhao, J. B. Tenenbaum, and A. Torralba, “Music gesture for visual sound separation,” in Proc. of CVPR, 2020. [[paper]](https://arxiv.org/pdf/2004.09476.pdf) [[project page]](http://music-gesture.csail.mit.edu) [[demo]](https://www.youtube.com/watch?v=m6fo2A7qGQM&feature=emb_title)

* R. Gao, R. Feris, and K. Grauman, “Learning to separate object sounds by watching unlabeled video,” in Proc. of ECCV, 2018. [[paper]](https://arxiv.org/pdf/1804.01665.pdf) [[project page]](http://vision.cs.utexas.edu/projects/separating_object_sounds/) [[demo 1]](https://www.youtube.com/watch?v=skeTh2B9rj0&feature=emb_title) [[demo 2]](https://www.youtube.com/watch?v=MlefGnofr4I&feature=emb_title) [[code]](https://github.com/rhgao/Deep-MIML-Network)

* R. Gao and K. Grauman, “2.5D visual sound,” in Proc. of CVPR, 2019. [[paper]](https://arxiv.org/pdf/1812.04204.pdf) [[project page]](http://vision.cs.utexas.edu/projects/2.5D_visual_sound/) [[demo]](https://www.youtube.com/watch?v=Wrx3pv_ixdI&feature=emb_title) [[code]](https://github.com/facebookresearch/2.5D-Visual-Sound)

* R. Gao and K. Grauman, “Co-separating sounds of visual objects,” in Proc. of ICCV, 2019. [[paper]](https://arxiv.org/abs/1904.07750) [[project page]](http://vision.cs.utexas.edu/projects/coseparation/) [[demo]](https://www.youtube.com/watch?v=Tdm5K65WL2I&feature=emb_title) [[code]](https://github.com/rhgao/co-separation)

* S. Parekh, A. Ozerov, S. Essid, N. Q. Duong, P. Pérez, and G. Richard, “Identify, locate and separate: Audio-visual object extraction in large video collections using weak supervision,” in Proc. of WASPAA, 2019. [[paper]](https://arxiv.org/pdf/1811.04000.pdf) [[project page]](https://perso.telecom-paristech.fr/sparekh/icassp2019.html) [[demo]](https://perso.telecom-paristech.fr/sparekh/icassp2019.html)

* A. Rouditchenko, H. Zhao, C. Gan, J. McDermott, and A. Torralba, “Self-supervised audio-visual co-segmentation,” in Proc. of ICASSP, 2019. [[paper]](https://arxiv.org/pdf/1904.09013.pdf)

* O. Slizovskaia, G. Haro, and E. Gómez, “Conditioned source separation for music instrument performances,” arXiv preprint arXiv:2004.03873, 2020. [[paper]](https://arxiv.org/pdf/2004.03873.pdf) [[project page]](https://veleslavia.github.io/conditioned-u-net/) [[demo]](https://www.youtube.com/watch?v=qJdsqh2y2C8&feature=emb_title)[[code]](https://github.com/veleslavia/conditioned-u-net)

* X. Xu, B. Dai, and D. Lin, “Recursive visual sound separation using minus-plus net,” in Proc. of ICCV, 2019. [[paper]](https://arxiv.org/pdf/1908.11602.pdf) [[demo]](https://www.youtube.com/watch?v=io_myrxtA4I)

* H. Zhao, C. Gan, W.-C. Ma, and A. Torralba, “The sound of motions,” in Proc. of ICCV, 2019. [[paper]](https://arxiv.org/pdf/1904.05979.pdf) [[demo]](http://people.csail.mit.edu/hangzhao/videos/SoM_supp.mp4)

* H. Zhao, C. Gan, A. Rouditchenko, C. Vondrick, J. McDermott, and A. Torralba, “The sound of pixels,” in Proc. of ECCV, 2018. [[paper]](https://arxiv.org/pdf/1804.03160.pdf) [[project page]](http://sound-of-pixels.csail.mit.edu) [[demo 1]](https://www.youtube.com/watch?v=2eVDLEQlKD0&feature=emb_title) [[demo 2]](http://sound-of-pixels.csail.mit.edu)[[code]](https://github.com/hangzhaomit/Sound-of-Pixels)

* L. Zhu and E. Rahtu, “Separating sounds from a single image,” arXiv preprint arXiv:2007.07984, 2020. [[paper]](https://arxiv.org/pdf/2007.07984.pdf) [[project page]](https://ly-zhu.github.io/separating-sounds-from-single-image)

* L. Zhu and E. Rahtu, “Visually guided sound source separation using cascaded oppo- nent filter network,” arXiv preprint arXiv:2006.03028, 2020. [[paper]](https://arxiv.org/pdf/2006.03028.pdf) [[project page]](https://ly-zhu.github.io/cof-net)


## Related Overview Articles

* J. Rincón-Trujillo and D. M. Córdova-Esparza, “Analysis of speech separation methods based on deep learning,” International Journal of Computer Applications, vol. 148, no. 9, pp. 21–29, 2019. [[paper]](https://pdfs.semanticscholar.org/887e/a4a6101cbd3d76dbd031dd7ed96604c4deb0.pdf)

* B. Rivet, W. Wang, S. M. Naqvi, and J. A. Chambers, “Audiovisual speech source separation: An overview of key methodologies,” IEEE Signal Processing Magazine, vol. 31, no. 3, pp. 125–134, 2014. [[paper]](https://ieeexplore.ieee.org/abstract/document/6784034)

* T. M. F. Taha and A. Hussain, “A survey on techniques for enhancing speech,” International Journal of Computer Applications, vol. 179, no. 17, pp. 1–14, 2018. [[paper]](https://www.researchgate.net/profile/Amir_Hussain5/publication/323223280_A_Survey_on_Techniques_for_Enhancing_Speech/links/5af053e0458515f599848530/A-Survey-on-Techniques-for-Enhancing-Speech.pdf)

* D. L. Wang and J. Chen, “Supervised speech separation based on deep learning: An overview,” IEEE/ACM Transactions on Audio, Speech, and Language Processing, 2018. [[paper]](https://arxiv.org/pdf/1708.07524.pdf)

* H. Zhu, M. Luo, R. Wang, A. Zheng, and R. He, “Deep audio-visual learning: A survey,” arXiv preprint arXiv:2001.04758, 2020. [[paper]](https://arxiv.org/pdf/2001.04758.pdf)





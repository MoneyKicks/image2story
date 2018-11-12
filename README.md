# neuraltalk_plus_charcnn
<div>A project for telling stories according to images in some particular style (e.g: Shakespeare, Jinyong Novel)</div><div><br></div><div>This project is for the class final project of deep learning.</div><div><br></div><div><b>Project name:</b></div><div><div>看图讲故事+文字风格生成</div><div>(image caption for key words + shakespeare poem generator)</div><div>Image to Styled Story Telling</div><div><br></div><div><div><b>Ideas:</b></div><div><strike>image caption minus original style for key words extracting -&gt; key words feeding to char-rnn（X）</strike></div><div>image caption minus original style for key words -&gt; change original style into shakespeare style (x-b+c)</div><div><strike>image caption for sentence -&gt;sentence feeding to char-rnn（X）</strike></div></div><div><br></div><div><div><b>Model structure:</b></div><div>image caption for key words extracting</div><div>char rnn for style text generation (shakespeare style for example)</div><div>key words feeding to char rnn</div><div>（further）Chinese version of image style story telling（martial arts novel for example）</div></div><div><br></div><div><div><b>Todo list:</b></div><div>Nov 10 - Nov 17: Investigation</div><div>Nov 18 - Nov 24: Build up codebase and get down to datasets</div><div>Nov 24 - Nov 30: develop xx idea</div><div>Dec 01 - Dec 08: experiments</div><div>Dec 09 - Dec 16: paper writing</div></div><div><br></div><div><div><b>Dataset:</b></div><div>MS COCO,&nbsp;</div></div><div><br></div><b></b></div><div><b>Reference:</b></div><div><div><b>Links：</b></div><div>neural_talk:</div><div>github_neural-storyteller(basing on caffe, providing useful ideas): https://github.com/ryankiros/neural-storyteller</div><div>github_neuraltalk: https://github.com/karpathy/neuraltalk</div><div>github_neuraltalk2: https://github.com/karpathy/neuraltalk2</div><div>image caption:</div><div>github_imagecaption: https://github.com/boluoyu/ImageCaption</div><div>github_imagecaption with pytorch: https://github.com/ruotianluo/ImageCaptioning.pytorch</div><div>char-rnn:</div><div>github_shakespeare: https://github.com/martin-gorner/tensorflow-rnn-shakespeare</div><div><br></div><div><b>Paper:</b></div><div><div style=""><b>Image caption:</b></div></div><div>Karpathy, A., &amp; Li, F. F. (2015). Deep visual-semantic alignments for generating image descriptions. Computer Vision and Pattern Recognition(pp.3128-3137). IEEE. https://cs.stanford.edu/people/karpathy/cvpr2015.pdf</div><div>Mao, J., Xu, W., Yang, Y., Wang, J., Huang, Z., &amp; Yuille, A. (2014). Deep captioning with multimodal recurrent neural networks (m-rnn). Eprint Arxiv. http://zhihenghuang.com/publications/m-RNN_iclr.pdf</div></div><div><div><b>Grammatical Error Correction:</b></div><div>Chollampatt, S., &amp; Ng, H. T. (2018). A multilayer convolutional encoder-decoder neural network for grammatical Error Correction</div><div>http://cn.arxiv.org/pdf/1801.08831</div><div>Chollampatt, S., Taghipour, K., &amp; Ng, H. T. (2016). Neural network translation models for grammatical error correction.</div><div>http://cn.arxiv.org/pdf/1606.00189</div><div>Neural Sequence-Labelling Models for Grammatical Error Correction</div><div>http://aclweb.org/anthology/D17-1297</div></div>

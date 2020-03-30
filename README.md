# Classifier-Using-Core-Implementation-of-Tensorflow
<b>Objective:</b>
<li> Classification of the Fashion MNIST Dataset</li>

<h2>Deep Learning Model Implemented</h2>
<h3> 1st Colvolutional Layer </h3>
<li> convulation layer 1 </li>
<li> 28x28x1 </li>
<li> 10 kernel </li>
<li> stride 1 </li>
<li> filter_size = 3x3 </li>
<li> padding valid </li>
<li> n_out x n_out x n_filter = 26x26x10 </li>
<li> filter_shape = 4D Tensor = [fHeight, fWidth, nChannels, numFilters] = [3,3,1,10] </li>

<h2>Max Pooling Layer</h2>
<li> stride(2,2)</li>
<li> poolSize = (2x2)</li>
<li> out = 13x13x10</li>

<h3> 2nd Colvolutional Layer </h3>
<li> convulation layer 1 </li>
<li> 13x13x10 </li>
<li> 20 kernel </li>
<li> stride 1 </li>
<li> filter_size = 3x3 </li>
<li> padding valid </li>
<li> n_out x n_out x n_filter = 11x11x20 </li>
<li> filter_shape = 4D Tensor = [fHeight, fWidth, nChannels, numFilters] = [3,3,1,20] </li>

<h2>Max Pooling Layer</h2>
<li> stride(2,2)</li>
<li> poolSize = (2x2)</li>
<li> out = 6x6x20</li>

<h2>Flattening</h2>
<li> input = 6x6x20</li>
<li> output = 720x1</li>


## Example Images

The images below show examples for most augmentation techniques.

Values written in the form `(a, b)` denote a uniform distribution,
i.e. the value is randomly picked from the interval `[a, b]`.
Line strings are supported by all augmenters, but are not explicitly visualized
here.

<table>

<tr><td colspan="5"><strong>meta</strong></td></tr>
<tr>
<td colspan="1"><sub>Noop</sub></td>
<td colspan="1"><sub>ChannelShuffle</sub></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/noop.gif" height="148" width="100" alt="Noop"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/channelshuffle.gif" height="148" width="100" alt="ChannelShuffle"></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>arithmetic</strong></td></tr>
<tr>
<td colspan="1"><sub>Add</sub></td>
<td colspan="1"><sub>Add<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>AdditiveGaussianNoise</sub></td>
<td colspan="1"><sub>AdditiveGaussianNoise<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>AdditiveLaplaceNoise</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/add.gif" height="148" width="100" alt="Add"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/add_per_channel_true.gif" height="148" width="100" alt="Add per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/additivegaussiannoise.gif" height="148" width="100" alt="AdditiveGaussianNoise"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/additivegaussiannoise_per_channel_true.gif" height="148" width="100" alt="AdditiveGaussianNoise per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/additivelaplacenoise.gif" height="148" width="100" alt="AdditiveLaplaceNoise"></td>
</tr>
<tr>
<td colspan="1"><sub>AdditiveLaplaceNoise<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>AdditivePoissonNoise</sub></td>
<td colspan="1"><sub>AdditivePoissonNoise<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>Multiply</sub></td>
<td colspan="1"><sub>Multiply<br/>(per_channel=True)</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/additivelaplacenoise_per_channel_true.gif" height="148" width="100" alt="AdditiveLaplaceNoise per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/additivepoissonnoise.gif" height="148" width="100" alt="AdditivePoissonNoise"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/additivepoissonnoise_per_channel_true.gif" height="148" width="100" alt="AdditivePoissonNoise per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/multiply.gif" height="148" width="100" alt="Multiply"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/multiply_per_channel_true.gif" height="148" width="100" alt="Multiply per_channel=True"></td>
</tr>
<tr>
<td colspan="1"><sub>Dropout</sub></td>
<td colspan="1"><sub>Dropout<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>CoarseDropout<br/>(p=0.2)</sub></td>
<td colspan="1"><sub>CoarseDropout<br/>(p=0.2, per_channel=True)</sub></td>
<td colspan="1"><sub>ImpulseNoise</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/dropout.gif" height="148" width="100" alt="Dropout"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/dropout_per_channel_true.gif" height="148" width="100" alt="Dropout per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/coarsedropout_p_0_2.gif" height="148" width="100" alt="CoarseDropout p=0.2"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/coarsedropout_p_0_2_per_channel_true.gif" height="148" width="100" alt="CoarseDropout p=0.2, per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/impulsenoise.gif" height="148" width="100" alt="ImpulseNoise"></td>
</tr>
<tr>
<td colspan="1"><sub>SaltAndPepper</sub></td>
<td colspan="1"><sub>Salt</sub></td>
<td colspan="1"><sub>Pepper</sub></td>
<td colspan="1"><sub>CoarseSaltAndPepper<br/>(p=0.2)</sub></td>
<td colspan="1"><sub>CoarseSalt<br/>(p=0.2)</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/saltandpepper.gif" height="148" width="100" alt="SaltAndPepper"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/salt.gif" height="148" width="100" alt="Salt"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/pepper.gif" height="148" width="100" alt="Pepper"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/coarsesaltandpepper_p_0_2.gif" height="148" width="100" alt="CoarseSaltAndPepper p=0.2"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/coarsesalt_p_0_2.gif" height="148" width="100" alt="CoarseSalt p=0.2"></td>
</tr>
<tr>
<td colspan="1"><sub>CoarsePepper<br/>(p=0.2)</sub></td>
<td colspan="1"><sub>Invert</sub></td>
<td colspan="1"><sub>Invert<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>JpegCompression</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/coarsepepper_p_0_2.gif" height="148" width="100" alt="CoarsePepper p=0.2"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/invert.gif" height="148" width="100" alt="Invert"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/invert_per_channel_true.gif" height="148" width="100" alt="Invert per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/jpegcompression.gif" height="148" width="100" alt="JpegCompression"></td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>blend</strong></td></tr>
<tr>
<td colspan="1"><sub>Alpha<br/>with EdgeDetect(1.0)</sub></td>
<td colspan="1"><sub>Alpha<br/>with EdgeDetect(1.0)<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>SimplexNoiseAlpha<br/>with EdgeDetect(1.0)</sub></td>
<td colspan="1"><sub>FrequencyNoiseAlpha<br/>with EdgeDetect(1.0)</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/alpha_with_edgedetect_1_0.gif" height="148" width="100" alt="Alpha with EdgeDetect1.0"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/alpha_with_edgedetect_1_0_per_channel_true.gif" height="148" width="100" alt="Alpha with EdgeDetect1.0 per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/simplexnoisealpha_with_edgedetect_1_0.gif" height="148" width="100" alt="SimplexNoiseAlpha with EdgeDetect1.0"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/frequencynoisealpha_with_edgedetect_1_0.gif" height="148" width="100" alt="FrequencyNoiseAlpha with EdgeDetect1.0"></td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>blur</strong></td></tr>
<tr>
<td colspan="1"><sub>GaussianBlur</sub></td>
<td colspan="1"><sub>AverageBlur</sub></td>
<td colspan="1"><sub>MedianBlur</sub></td>
<td colspan="1"><sub>BilateralBlur<br/>(sigma_color=250,<br/>sigma_space=250)</sub></td>
<td colspan="1"><sub>MotionBlur<br/>(angle=0)</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/gaussianblur.gif" height="148" width="100" alt="GaussianBlur"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/averageblur.gif" height="148" width="100" alt="AverageBlur"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/medianblur.gif" height="148" width="100" alt="MedianBlur"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/bilateralblur_sigma_color_250_sigma_space_250.gif" height="148" width="100" alt="BilateralBlur sigma_color=250, sigma_space=250"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/motionblur_angle_0.gif" height="148" width="100" alt="MotionBlur angle=0"></td>
</tr>
<tr>
<td colspan="1"><sub>MotionBlur<br/>(k=5)</sub></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/motionblur_k_5.gif" height="148" width="100" alt="MotionBlur k=5"></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>color</strong></td></tr>
<tr>
<td colspan="1"><sub>MultiplyHueAndSaturation</sub></td>
<td colspan="1"><sub>MultiplyHue</sub></td>
<td colspan="1"><sub>MultiplySaturation</sub></td>
<td colspan="1"><sub>AddToHueAndSaturation</sub></td>
<td colspan="1"><sub>AddToHue</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/multiplyhueandsaturation.gif" height="148" width="100" alt="MultiplyHueAndSaturation"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/multiplyhue.gif" height="148" width="100" alt="MultiplyHue"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/multiplysaturation.gif" height="148" width="100" alt="MultiplySaturation"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/addtohueandsaturation.gif" height="148" width="100" alt="AddToHueAndSaturation"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/addtohue.gif" height="148" width="100" alt="AddToHue"></td>
</tr>
<tr>
<td colspan="1"><sub>AddToSaturation</sub></td>
<td colspan="1"><sub>Grayscale</sub></td>
<td colspan="1"><sub>KMeansColorQuantization<br/>(to_colorspace=RGB)</sub></td>
<td colspan="1"><sub>UniformColorQuantization<br/>(to_colorspace=RGB)</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/addtosaturation.gif" height="148" width="100" alt="AddToSaturation"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/grayscale.gif" height="148" width="100" alt="Grayscale"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/kmeanscolorquantization_to_colorspace_rgb.gif" height="148" width="100" alt="KMeansColorQuantization to_colorspace=RGB"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/uniformcolorquantization_to_colorspace_rgb.gif" height="148" width="100" alt="UniformColorQuantization to_colorspace=RGB"></td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>contrast</strong></td></tr>
<tr>
<td colspan="1"><sub>GammaContrast</sub></td>
<td colspan="1"><sub>GammaContrast<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>SigmoidContrast<br/>(cutoff=0.5)</sub></td>
<td colspan="1"><sub>SigmoidContrast<br/>(gain=10)</sub></td>
<td colspan="1"><sub>SigmoidContrast<br/>(per_channel=True)</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/gammacontrast.gif" height="148" width="100" alt="GammaContrast"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/gammacontrast_per_channel_true.gif" height="148" width="100" alt="GammaContrast per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/sigmoidcontrast_cutoff_0_5.gif" height="148" width="100" alt="SigmoidContrast cutoff=0.5"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/sigmoidcontrast_gain_10.gif" height="148" width="100" alt="SigmoidContrast gain=10"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/sigmoidcontrast_per_channel_true.gif" height="148" width="100" alt="SigmoidContrast per_channel=True"></td>
</tr>
<tr>
<td colspan="1"><sub>LogContrast</sub></td>
<td colspan="1"><sub>LogContrast<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>LinearContrast</sub></td>
<td colspan="1"><sub>LinearContrast<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>AllChannels-<br/>HistogramEqualization</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/logcontrast.gif" height="148" width="100" alt="LogContrast"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/logcontrast_per_channel_true.gif" height="148" width="100" alt="LogContrast per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/linearcontrast.gif" height="148" width="100" alt="LinearContrast"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/linearcontrast_per_channel_true.gif" height="148" width="100" alt="LinearContrast per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/allchannels_histogramequalization.gif" height="148" width="100" alt="AllChannels- HistogramEqualization"></td>
</tr>
<tr>
<td colspan="1"><sub>HistogramEqualization</sub></td>
<td colspan="1"><sub>AllChannelsCLAHE</sub></td>
<td colspan="1"><sub>AllChannelsCLAHE<br/>(per_channel=True)</sub></td>
<td colspan="1"><sub>CLAHE</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/histogramequalization.gif" height="148" width="100" alt="HistogramEqualization"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/allchannelsclahe.gif" height="148" width="100" alt="AllChannelsCLAHE"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/allchannelsclahe_per_channel_true.gif" height="148" width="100" alt="AllChannelsCLAHE per_channel=True"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/clahe.gif" height="148" width="100" alt="CLAHE"></td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>convolutional</strong></td></tr>
<tr>
<td colspan="1"><sub>Sharpen<br/>(alpha=1)</sub></td>
<td colspan="1"><sub>Emboss<br/>(alpha=1)</sub></td>
<td colspan="1"><sub>EdgeDetect</sub></td>
<td colspan="1"><sub>DirectedEdgeDetect<br/>(alpha=1)</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/sharpen_alpha_1.gif" height="148" width="100" alt="Sharpen alpha=1"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/emboss_alpha_1.gif" height="148" width="100" alt="Emboss alpha=1"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/edgedetect.gif" height="148" width="100" alt="EdgeDetect"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/directededgedetect_alpha_1.gif" height="148" width="100" alt="DirectedEdgeDetect alpha=1"></td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>edges</strong></td></tr>
<tr>
<td colspan="1"><sub>Canny</sub></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/canny.gif" height="148" width="100" alt="Canny"></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>flip</strong></td></tr>
<tr>
<td colspan="2"><sub>Fliplr</sub></td>
<td colspan="2"><sub>Flipud</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/fliplr.gif" height="148" width="300" alt="Fliplr"></td>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/flipud.gif" height="148" width="300" alt="Flipud"></td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>geometric</strong></td></tr>
<tr>
<td colspan="2"><sub>Affine</sub></td>
<td colspan="2"><sub>Affine: Modes</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/affine.gif" height="148" width="300" alt="Affine"></td>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/affine_modes.gif" height="148" width="300" alt="Affine: Modes"></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><sub>Affine: cval</sub></td>
<td colspan="2"><sub>PiecewiseAffine</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/affine_cval.gif" height="148" width="300" alt="Affine: cval"></td>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/piecewiseaffine.gif" height="148" width="300" alt="PiecewiseAffine"></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><sub>PerspectiveTransform</sub></td>
<td colspan="2"><sub>ElasticTransformation<br/>(sigma=0.2)</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/perspectivetransform.gif" height="148" width="300" alt="PerspectiveTransform"></td>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/elastictransformation_sigma_0_2.gif" height="148" width="300" alt="ElasticTransformation sigma=0.2"></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><sub>ElasticTransformation<br/>(sigma=5.0)</sub></td>
<td colspan="2"><sub>Rot90</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/elastictransformation_sigma_5_0.gif" height="148" width="300" alt="ElasticTransformation sigma=5.0"></td>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/rot90.gif" height="148" width="300" alt="Rot90"></td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>pooling</strong></td></tr>
<tr>
<td colspan="1"><sub>AveragePooling</sub></td>
<td colspan="1"><sub>MaxPooling</sub></td>
<td colspan="1"><sub>MinPooling</sub></td>
<td colspan="1"><sub>MedianPooling</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/averagepooling.gif" height="148" width="100" alt="AveragePooling"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/maxpooling.gif" height="148" width="100" alt="MaxPooling"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/minpooling.gif" height="148" width="100" alt="MinPooling"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/medianpooling.gif" height="148" width="100" alt="MedianPooling"></td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>segmentation</strong></td></tr>
<tr>
<td colspan="1"><sub>Superpixels<br/>(p_replace=1)</sub></td>
<td colspan="1"><sub>Superpixels<br/>(n_segments=100)</sub></td>
<td colspan="1"><sub>UniformVoronoi</sub></td>
<td colspan="1"><sub>RegularGridVoronoi: rows/cols<br/>(p_drop_points=0)</sub></td>
<td colspan="1"><sub>RegularGridVoronoi: p_drop_points<br/>(n_rows=n_cols=30)</sub></td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/superpixels_p_replace_1.gif" height="148" width="100" alt="Superpixels p_replace=1"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/superpixels_n_segments_100.gif" height="148" width="100" alt="Superpixels n_segments=100"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/uniformvoronoi.gif" height="148" width="100" alt="UniformVoronoi"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/regulargridvoronoi_rows_cols_p_drop_points_0.gif" height="148" width="100" alt="RegularGridVoronoi: rows/cols p_drop_points=0"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/regulargridvoronoi_p_drop_points_n_rows_n_cols_30.gif" height="148" width="100" alt="RegularGridVoronoi: p_drop_points n_rows=n_cols=30"></td>
</tr>
<tr>
<td colspan="1"><sub>RegularGridVoronoi: p_replace<br/>(n_rows=n_cols=16)</sub></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/regulargridvoronoi_p_replace_n_rows_n_cols_16.gif" height="148" width="100" alt="RegularGridVoronoi: p_replace n_rows=n_cols=16"></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>size</strong></td></tr>
<tr>
<td colspan="2"><sub>CropAndPad</sub></td>
<td colspan="2"><sub>Crop</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/cropandpad.gif" height="148" width="300" alt="CropAndPad"></td>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/crop.gif" height="148" width="300" alt="Crop"></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><sub>Pad</sub></td>
<td colspan="2"><sub>PadToFixedSize<br/>(height'=height+32,<br/>width'=width+32)</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/pad.gif" height="148" width="300" alt="Pad"></td>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/padtofixedsize_height_height_32_width_width_32.gif" height="148" width="300" alt="PadToFixedSize height'=height+32, width'=width+32"></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><sub>CropToFixedSize<br/>(height'=height-32,<br/>width'=width-32)</sub></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="2"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/croptofixedsize_height_height_32_width_width_32.gif" height="148" width="300" alt="CropToFixedSize height'=height-32, width'=width-32"></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr><td colspan="5"><strong>weather</strong></td></tr>
<tr>
<td colspan="1"><sub>FastSnowyLandscape<br/>(lightness_multiplier=2.0)</sub></td>
<td colspan="1"><sub>Clouds</sub></td>
<td colspan="1"><sub>Fog</sub></td>
<td colspan="1"><sub>Snowflakes</sub></td>
<td>&nbsp;</td>
</tr>
<tr>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/fastsnowylandscape_lightness_multiplier_2_0.gif" height="144" width="128" alt="FastSnowyLandscape lightness_multiplier=2.0"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/clouds.gif" height="144" width="128" alt="Clouds"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/fog.gif" height="144" width="128" alt="Fog"></td>
<td colspan="1"><img src="https://raw.githubusercontent.com/aleju/imgaug-doc/master/readme_images/augmenter_videos/snowflakes.gif" height="144" width="128" alt="Snowflakes"></td>
<td>&nbsp;</td>
</tr>

</table>



<a name="code_examples"/>


## Code Examples

### Example: Simple Training Setting

A standard machine learning situation.
Train on batches of images and augment each batch via crop, horizontal
flip ("Fliplr") and gaussian blur:
```python
import numpy as np
import imgaug.augmenters as iaa

def load_batch(batch_idx):
    # dummy function, implement this
    # Return a numpy array of shape (N, height, width, #channels)
    # or a list of (height, width, #channels) arrays (may have different image
    # sizes).
    # Images should be in RGB for colorspace augmentations.
    # (cv2.imread() returns BGR!)
    # Images should usually be in uint8 with values from 0-255.
    return np.zeros((128, 32, 32, 3), dtype=np.uint8) + (batch_idx % 255)

def train_on_images(images):
    # dummy function, implement this
    pass

# Pipeline:
# (1) Crop images from each side by 1-16px, do not resize the results
#     images back to the input size. Keep them at the cropped size.
# (2) Horizontally flip 50% of the images.
# (3) Blur images using a gaussian kernel with sigma between 0.0 and 3.0.
seq = iaa.Sequential([
    iaa.Crop(px=(1, 16), keep_size=False),
    iaa.Fliplr(0.5),
    iaa.GaussianBlur(sigma=(0, 3.0))
])

for batch_idx in range(100):
    images = load_batch(batch_idx)
    images_aug = seq(images=images)  # done by the library
    train_on_images(images_aug)
```


### Example: Very Complex Augmentation Pipeline

Apply a very heavy augmentation pipeline to images (used to create the image 
at the very top of this readme):
```python
import numpy as np
import imgaug as ia
import imgaug.augmenters as iaa

# random example images
images = np.random.randint(0, 255, (16, 128, 128, 3), dtype=np.uint8)

# Sometimes(0.5, ...) applies the given augmenter in 50% of all cases,
# e.g. Sometimes(0.5, GaussianBlur(0.3)) would blur roughly every second image.
sometimes = lambda aug: iaa.Sometimes(0.5, aug)

# Define our sequence of augmentation steps that will be applied to every image
# All augmenters with per_channel=0.5 will sample one value _per image_
# in 50% of all cases. In all other cases they will sample new values
# _per channel_.

seq = iaa.Sequential(
    [
        # apply the following augmenters to most images
        iaa.Fliplr(0.5), # horizontally flip 50% of all images
        iaa.Flipud(0.2), # vertically flip 20% of all images
        # crop images by -5% to 10% of their height/width
        sometimes(iaa.CropAndPad(
            percent=(-0.05, 0.1),
            pad_mode=ia.ALL,
            pad_cval=(0, 255)
        )),
        sometimes(iaa.Affine(
            scale={"x": (0.8, 1.2), "y": (0.8, 1.2)}, # scale images to 80-120% of their size, individually per axis
            translate_percent={"x": (-0.2, 0.2), "y": (-0.2, 0.2)}, # translate by -20 to +20 percent (per axis)
            rotate=(-45, 45), # rotate by -45 to +45 degrees
            shear=(-16, 16), # shear by -16 to +16 degrees
            order=[0, 1], # use nearest neighbour or bilinear interpolation (fast)
            cval=(0, 255), # if mode is constant, use a cval between 0 and 255
            mode=ia.ALL # use any of scikit-image's warping modes (see 2nd image from the top for examples)
        )),
        # execute 0 to 5 of the following (less important) augmenters per image
        # don't execute all of them, as that would often be way too strong
        iaa.SomeOf((0, 5),
            [
                sometimes(iaa.Superpixels(p_replace=(0, 1.0), n_segments=(20, 200))), # convert images into their superpixel representation
                iaa.OneOf([
                    iaa.GaussianBlur((0, 3.0)), # blur images with a sigma between 0 and 3.0
                    iaa.AverageBlur(k=(2, 7)), # blur image using local means with kernel sizes between 2 and 7
                    iaa.MedianBlur(k=(3, 11)), # blur image using local medians with kernel sizes between 2 and 7
                ]),
                iaa.Sharpen(alpha=(0, 1.0), lightness=(0.75, 1.5)), # sharpen images
                iaa.Emboss(alpha=(0, 1.0), strength=(0, 2.0)), # emboss images
                # search either for all edges or for directed edges,
                # blend the result with the original image using a blobby mask
                iaa.SimplexNoiseAlpha(iaa.OneOf([
                    iaa.EdgeDetect(alpha=(0.5, 1.0)),
                    iaa.DirectedEdgeDetect(alpha=(0.5, 1.0), direction=(0.0, 1.0)),
                ])),
                iaa.AdditiveGaussianNoise(loc=0, scale=(0.0, 0.05*255), per_channel=0.5), # add gaussian noise to images
                iaa.OneOf([
                    iaa.Dropout((0.01, 0.1), per_channel=0.5), # randomly remove up to 10% of the pixels
                    iaa.CoarseDropout((0.03, 0.15), size_percent=(0.02, 0.05), per_channel=0.2),
                ]),
                iaa.Invert(0.05, per_channel=True), # invert color channels
                iaa.Add((-10, 10), per_channel=0.5), # change brightness of images (by -10 to 10 of original value)
                iaa.AddToHueAndSaturation((-20, 20)), # change hue and saturation
                # either change the brightness of the whole image (sometimes
                # per channel) or change the brightness of subareas
                iaa.OneOf([
                    iaa.Multiply((0.5, 1.5), per_channel=0.5),
                    iaa.FrequencyNoiseAlpha(
                        exponent=(-4, 0),
                        first=iaa.Multiply((0.5, 1.5), per_channel=True),
                        second=iaa.LinearContrast((0.5, 2.0))
                    )
                ]),
                iaa.LinearContrast((0.5, 2.0), per_channel=0.5), # improve or worsen the contrast
                iaa.Grayscale(alpha=(0.0, 1.0)),
                sometimes(iaa.ElasticTransformation(alpha=(0.5, 3.5), sigma=0.25)), # move pixels locally around (with random strengths)
                sometimes(iaa.PiecewiseAffine(scale=(0.01, 0.05))), # sometimes move parts of the image around
                sometimes(iaa.PerspectiveTransform(scale=(0.01, 0.1)))
            ],
            random_order=True
        )
    ],
    random_order=True
)
images_aug = seq(images=images)
```


### Example: Augment Images and Keypoints

Augment images and keypoints/landmarks on the same images:
```python
import numpy as np
import imgaug.augmenters as iaa

images = np.zeros((2, 128, 128, 3), dtype=np.uint8)  # two example images
images[:, 64, 64, :] = 255
points = [
    [(10.5, 20.5)],  # points on first image
    [(50.5, 50.5), (60.5, 60.5), (70.5, 70.5)]  # points on second image
]

seq = iaa.Sequential([
    iaa.AdditiveGaussianNoise(scale=0.05*255),
    iaa.Affine(translate_px={"x": (1, 5)})
])

# augment keypoints and images
images_aug, points_aug = seq(images=images, keypoints=points)

print("Image 1 center", np.argmax(images_aug[0, 64, 64:64+6, 0]))
print("Image 2 center", np.argmax(images_aug[1, 64, 64:64+6, 0]))
print("Points 1", points_aug[0])
print("Points 2", points_aug[1])
```
Note that all coordinates in `imgaug` are subpixel-accurate, which is
why `x=0.5, y=0.5` denotes the center of the pixel of the top left pixel.


### Example: Augment Images and Bounding Boxes

```python
import numpy as np
import imgaug as ia
import imgaug.augmenters as iaa

images = np.zeros((2, 128, 128, 3), dtype=np.uint8)  # two example images
images[:, 64, 64, :] = 255
bbs = [
    [ia.BoundingBox(x1=10.5, y1=15.5, x2=30.5, y2=50.5)],
    [ia.BoundingBox(x1=10.5, y1=20.5, x2=50.5, y2=50.5),
     ia.BoundingBox(x1=40.5, y1=75.5, x2=70.5, y2=100.5)]
]

seq = iaa.Sequential([
    iaa.AdditiveGaussianNoise(scale=0.05*255),
    iaa.Affine(translate_px={"x": (1, 5)})
])

images_aug, bbs_aug = seq(images=images, bounding_boxes=bbs)
```


### Example: Augment Images and Polygons

```python
import numpy as np
import imgaug as ia
import imgaug.augmenters as iaa

images = np.zeros((2, 128, 128, 3), dtype=np.uint8)  # two example images
images[:, 64, 64, :] = 255
polygons = [
    [ia.Polygon([(10.5, 10.5), (50.5, 10.5), (50.5, 50.5)])],
    [ia.Polygon([(0.0, 64.5), (64.5, 0.0), (128.0, 128.0), (64.5, 128.0)])]
]

seq = iaa.Sequential([
    iaa.AdditiveGaussianNoise(scale=0.05*255),
    iaa.Affine(translate_px={"x": (1, 5)})
])

images_aug, polygons_aug = seq(images=images, polygons=polygons)
```


### Example: Augment Images and LineStrings

LineStrings are similar to polygons, but are not closed, may intersect with
themselves and don't have an inner area.
```python
import numpy as np
import imgaug as ia
import imgaug.augmenters as iaa

images = np.zeros((2, 128, 128, 3), dtype=np.uint8)  # two example images
images[:, 64, 64, :] = 255
ls = [
    [ia.LineString([(10.5, 10.5), (50.5, 10.5), (50.5, 50.5)])],
    [ia.LineString([(0.0, 64.5), (64.5, 0.0), (128.0, 128.0), (64.5, 128.0),
                    (128.0, 0.0)])]
]

seq = iaa.Sequential([
    iaa.AdditiveGaussianNoise(scale=0.05*255),
    iaa.Affine(translate_px={"x": (1, 5)})
])

images_aug, ls_aug = seq(images=images, line_strings=ls)
```


### Example: Augment Images and Heatmaps

Heatmaps are dense float arrays with values between `0.0` and `1.0`.
They can be used e.g. when training models to predict facial landmark
locations. Note that the heatmaps here have lower height and width than the
images. `imgaug` handles that case automatically. The crop pixel amounts will
be halved for the heatmaps.

```python
import numpy as np
import imgaug.augmenters as iaa

# Standard scenario: You have N RGB-images and additionally 21 heatmaps per
# image. You want to augment each image and its heatmaps identically.
images = np.random.randint(0, 255, (16, 128, 128, 3), dtype=np.uint8)
heatmaps = np.random.random(size=(16, 64, 64, 1)).astype(np.float32)

seq = iaa.Sequential([
    iaa.GaussianBlur((0, 3.0)),
    iaa.Affine(translate_px={"x": (-40, 40)}),
    iaa.Crop(px=(0, 10))
])

images_aug, heatmaps_aug = seq(images=images, heatmaps=heatmaps)
```


### Example: Augment Images and Segmentation Maps

This is similar to heatmaps, but the dense arrays have dtype `int32`.
Operations such as resizing will automatically use nearest neighbour
interpolation.

```python
import numpy as np
import imgaug.augmenters as iaa

# Standard scenario: You have N=16 RGB-images and additionally one segmentation
# map per image. You want to augment each image and its heatmaps identically.
images = np.random.randint(0, 255, (16, 128, 128, 3), dtype=np.uint8)
segmaps = np.random.randint(0, 10, size=(16, 64, 64, 1), dtype=np.int32)

seq = iaa.Sequential([
    iaa.GaussianBlur((0, 3.0)),
    iaa.Affine(translate_px={"x": (-40, 40)}),
    iaa.Crop(px=(0, 10))
])

images_aug, segmaps_aug = seq(images=images, segmentation_maps=segmaps)
```


### Example: Visualize Augmented Images

Quickly show example results of your augmentation sequence:
```python
import numpy as np
import imgaug.augmenters as iaa

images = np.random.randint(0, 255, (16, 128, 128, 3), dtype=np.uint8)
seq = iaa.Sequential([iaa.Fliplr(0.5), iaa.GaussianBlur((0, 3.0))])

# Show an image with 8*8 augmented versions of image 0 and 8*8 augmented
# versions of image 1. Identical augmentations will be applied to
# image 0 and 1.
seq.show_grid([images[0], images[1]], cols=8, rows=8)
```

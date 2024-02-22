# Image-Reconstruction-using-Near-and-Far-Receptive-Fields.

IMAGE RECONSTRUCTION USING NEAR AND FAR RECEPTIVE FIELDS

Image Inpainting improved a lot with the help of algorithms in deep learning. Image Inpainting will be very useful if the missing regions present in the document or 
an important image. Most widely used networks include an encoder-decoder architecture (sometimes with skip connections, allowing layers to skip layers) and a sizeable
receptive field, or one that is greater than the picture resolution. For picture inpainting jobs, the size of the surrounding areas needed to fill in different sorts 
of missing regions vary, and a very large receptive field is not always the ideal choice, especially for the neighbouring buildings and textures. Inpainting will be 
hindered by the broad receptive field's tendency to create more unsatisfactory completion outcomes. We developed a ground-breaking three-stage inpainting framework
with partial, small and large refinements based on these insights, which rethinks the picture inpainting process from the unique viewpoint of the receptive field. We first
employ an encoder-decoder network to gather rough early results. Then, to carry out the small refinement, we introduce a shallow deep model with a small receptive field, 
which can also lessen the impact of distant undesirable completion outcomes. To carry out the large refinement, we finally propose an attention-based encoder-decoder network
with a large receptive field. According to test results, our method performs better than the state of currently available technology for image inpainting on two popular 
datasets that are open to the public.

Language Used:Python
Library Used :Tensorflow
Software tool:Google colab

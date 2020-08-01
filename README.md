## CNN and GAN Comparison Study
By: Jacob Boness, Colton Davenport, Jamie Thomassen

To create tfrecords use dataset creator found here: https://github.com/daitan-innovation/cnn-audio-denoiser

Each notebook has running instructions.
Here's a typical Run Order -

1) Audio_Noiser.ipynb:
	* For this have:
		* A directory of noises
		* A directory of voices
		* A directory for the noisy voices
2) CNN.ipynb:
	* For this have:
		* A directory of tfRecords
		* A directory for checkpoints
3) GAN.ipynb:
	* For this have:
		* A directory of tfRecords
		* A directory for checkpoints
4) Audio_Denoiser.ipynb:
	* For this have:
		* A directory of noisy voices
		* The path of a checkpoint
		* A directory for denoised voices

Sources:

CNN: Daitan's Audio Denoiser - https://github.com/daitan-innovation/cnn-audio-denoiser

GAN: Pix2Pix - https://www.tensorflow.org/tutorials/generative/pix2pix

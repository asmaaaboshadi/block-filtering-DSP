# block-filtering-DSP
In digital signal processing (DSP), block filtering is a technique for processing
a signal by dividing it into smaller segments or blocks and applying a filter to
each block individually. This approach is particularly useful for processing
large signals or signals that are too long to be processed as a whole.


The overlap-save method is a technique used in digital signal processing (DSP) to
efficiently filter long signals using a finite impulse response (FIR) filter. It is particularly
useful when the signal is too long to be processed as a whole or when real-time
processing is required. The overlap-save method works by dividing the input signal into smaller overlapping
blocks. Each block is then circularly convolved with the FIR filter coefficients. The
circular convolution introduces some transient effects at the beginning and end of
each block. To eliminate these transients, the first few samples of each block are
discarded, and the remaining samples are saved and concatenated to form the output
signal.



The overlap-add method is a technique used in digital signal processing (DSP) to
efficiently filter long signals by dividing them into smaller blocks and combining
the filtered blocks while overlapping their ends. This method is particularly useful
for implementing linear convolution using fast Fourier transform (FFT)-based
circular convolution.


Comment: The overlap-add results are the same as the linear
convolution results. The filter of the overlap-add is better than the filter
of the over-lap save


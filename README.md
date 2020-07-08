# spiruleDSP
Julia Library  having DSP functions

### Signal Manipulation 

- alignsignals - Align two signals by delaying earliest signal
- bandpower    - Band power        
- cconv - Modulo-n circular convolution
- cceps - Complex cepstral analysis 
- chirp - Swept-frequency cosine
- convmtx - Convolution matrix
- cpsd - Cross power spectral density
- cusum - Detect small changes in mean using cumulative sum
- czt - Chirp Z-transform
- db - Convert energy or power measurements to decibels
- db2mag - Convert decibels to magnitude
- db2pow - Convert decibels to power
- dct - Discrete cosine transform
- decimate - Decimation — decrease sample rate by integer factor
- diric - Dirichlet or periodic sinc function
- downsample - Decrease sample rate by integer factor
- dtw - Distance between signals using dynamic time warping
- dutycycle - Duty cycle of pulse waveform
- emd - Empirical mode decomposition
- enbw - Equivalent noise bandwidth
- envelope - Signal envelope
- findchangepts - Find abrupt changes in signal
- finddelay - Estimate delay(s) between signals
- findpeaks - Find local maxima
- findsignal - Find signal location using similarity search
- fillgaps - Fill gaps using autoregressive modeling
- fsst - Fourier synchrosqueezed transform
- fwht - Fast Walsh-Hadamard transform
- goertzel - Discrete Fourier transform with second-order Goertzel algorithm
- gmonopuls - Gaussian monopulse
- hht - Hilbert-Huang transform
- hilbert - Discrete-time analytic signal using Hilbert transform
- icceps - Inverse complex cepstrum
- idct - Inverse discrete cosine transform
- ifsst - Inverse Fourier synchrosqueezed transform
- ifwht - Inverse Fast Walsh-Hadamard transform
- instfreq - Estimate instantaneous frequency
- interp - Interpolation — increase sample rate by integer factor

### Filters

- bandpass
- bandstop 
- barthannwin - Modified Bartlett-Hann window
- bartlett - Bartlett window
- bilinear - Bilinear transformation method for analog-to-digital filter conversion
- bitrevorder - Permute data into bit-reversed order
- blackman - Blackman window
- blackmanharris - Minimum four-term Blackman-Harris window
- bohmanwin - Bohman window
- buffer - Buffer signal vector into matrix of data frames
- buttap - Butterworth filter prototype
- butter - Butterworth filter design
- buttord - Butterworth filter order and cutoff frequency
- cfirpm - Complex and nonlinear-phase equiripple FIR filter design
- cheb1ap - ChebyshevType I analog lowpass filter prototype
- cheb1ord - Chebyshev Type I filter order
- cheb2ap - ChebyshevType II analog lowpass filter prototype
- cheb2ord - Chebyshev Type II filter order
- chebwin - Chebyshev window
- cheby1 - Chebyshev Type I filter design
- cheby2 - Chebyshev Type II filter design
- ellip - Elliptic filter design
- ellipap - Elliptic analog lowpass filter prototype 
- ellipord - Minimum order for elliptic filters
- equiripple - Equiripple single-rate FIR filter from specification object
- eqtflength - Equalize lengths of transfer function's numerator and denominator
- falltime - Fall time of negative-going bilevel waveform transitions
- filtfilt - Zero-phase digital filtering
- filtic - Initial conditions for transposed direct-form II filter implementation
- fir - Window-based FIR filter design
- fir2 - Frequency sampling-based FIR filter design
- fircls - Constrained-least-squares FIR multiband filter design
- firls - Least-squares linear-phase FIR filter design
- firpm - Parks-McClellan optimal FIR filter design
- firpmord - Parks-McClellan optimal FIR filter order estimation
- flattopwin - Flat top weighted window
- freqs - Frequency response of analog filters
- freqz - Frequency response of digital filter
- gausswin - Gaussian window
- grpdelay - Average filter delay (group delay)
- hamming - Hamming window
- hann - Hanning window
- highpass - Highpass-filter signals
- impinvar - Impulse invariance method for analog-to-digital filter conversion
- impz - Impulse response of digital filter
- impzlength - Impulse response length
- intfilt - Interpolation FIR filter design
- kaiser - Kaiser window







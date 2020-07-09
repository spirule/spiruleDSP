# spiruleDSP
Julia Library  having DSP functions, syntax and usage kept identical to matlab DSP toolbox as far as possible.
In Development currently.

### Signal Analysis

- strips Strip plot

### Waveform Generation

- chirp Swept-frequency cosine
- diric	Dirichlet or periodic sinc function
- pulstran	Pulse train
- rectpuls	Sampled aperiodic rectangle
- sawtooth	Sawtooth or triangle wave
- sinc	Sinc function
- square	Square wave
- tripuls	Sampled aperiodic triangle

### Measurement and Feature Extraction

- envelope	Signal envelope
- meanfreq	Mean frequency
- medfreq	Median frequency
- peak2peak	Maximum-to-minimum difference
- peak2rms	Peak-magnitude-to-RMS ratio
- rms	Root-mean-square level
- rssq	Root-sum-of-squares level
- seqperiod	Compute period of sequence
- alignsignals	Align two signals by delaying earliest signal
- cusum	Detect small changes in mean using cumulative sum
- dtw	Distance between signals using dynamic time warping
- findchangepts	Find abrupt changes in signal
- finddelay	Estimate delay(s) between signals
- findpeaks	Find local maxima
- findsignal	Find signal location using similarity search

### Pulse and Transition Metrics

- dutycycle	Duty cycle of pulse waveform

### Spectral Measurements

- bandpower	Band power
- enbw	Equivalent noise bandwidth
- instfreq	Estimate instantaneous frequency
- meanfreq	Mean frequency
- medfreq	Median frequency

### Transforms

- dftmtx	Discrete Fourier transform matrix
- instfreq	Estimate instantaneous frequency
- czt	Chirp Z-transform
- goertzel	Discrete Fourier transform with second-order Goertzel algorithm
- dct	Discrete cosine transform
- idct	Inverse discrete cosine transform
- fwht	Fast Walsh-Hadamard transform
- ifwht	Inverse Fast Walsh-Hadamard transform
- hilbert	Discrete-time analytic signal using Hilbert transform
- emd	Empirical mode decomposition
- fsst	Fourier synchrosqueezed transform
- ifsst	Inverse Fourier synchrosqueezed transform
- hht	Hilbert-Huang transform
- cceps	Complex cepstral analysis
- icceps	Inverse complex cepstrum
- bitrevorder	Permute data into bit-reversed order
- digitrevorder	Permute input into digit-reversed order

### Correlation and Convolution

- corrmtx	Data matrix for autocorrelation matrix estimation
- xcorr2	2-D cross-correlation
- cconv	Modulo-n circular convolution
- convmtx	Convolution matrix
- alignsignals	Align two signals by delaying earliest signal

### Filters

- butter	Butterworth filter design
- buttord	Butterworth filter order and cutoff frequency
- cheby1	Chebyshev Type I filter design
- cheb1ord	Chebyshev Type I filter order
- cheby2	Chebyshev Type II filter design
- cheb2ord	Chebyshev Type II filter order
- ellip	Elliptic filter design
- ellipord	Minimum order for elliptic filters
- fir1	Window-based FIR filter design
- fir2	Frequency sampling-based FIR filter design
- fircls	Constrained-least-squares FIR multiband filter design
- fircls1	Constrained-least-squares linear-phase FIR lowpass and highpass filter design
- firls	Least-squares linear-phase FIR filter design
- firpm	Parks-McClellan optimal FIR filter design
- firpmord	Parks-McClellan optimal FIR filter order estimation

### Digital Filter Analysis

- freqz	Frequency response of digital filter
- grpdelay	Average filter delay (group delay)
- phasedelay	Phase delay of digital filter
- phasez	Phase response of digital filter
- zerophase	Zero-phase response of digital filter
- zplane	Zero-pole plot for discrete-time systems
- impz	Impulse response of digital filter
- impzlength	Impulse response length
- stepz	Step response of digital filter
- filtord	Filter order

### Digital Filtering

- bandpass	Bandpass-filter signals
- bandstop	Bandstop-filter signals
- highpass	Highpass-filter signals
- lowpass	Lowpass-filter signals

### Multirate Signals Processing

- decimate	Decimation — decrease sample rate by integer factor
- downsample	Decrease sample rate by integer factor
- fillgaps	Fill gaps using autoregressive modeling
- interp	Interpolation — increase sample rate by integer factor
- resample	Resample uniform or nonuniform data to new fixed rate
- upsample	Increase sample rate by integer factor

### Windows

- barthannwin	Modified Bartlett-Hann window
- bartlett	Bartlett window
- blackman	Blackman window
- blackmanharris	Minimum four-term Blackman-Harris window
- bohmanwin	Bohman window
- chebwin	Chebyshev window
- enbw	Equivalent noise bandwidth
- flattopwin	Flat top weighted window
- gausswin	Gaussian window
- hamming	Hamming window
- hann	Hann (Hanning) window
- kaiser	Kaiser window
- nuttallwin	Nuttall-defined minimum 4-term Blackman-Harris window
- parzenwin	Parzen (de la Vallée Poussin) window
- rectwin	Rectangular window
- taylorwin	Taylor window
- triang	Triangular window
- tukeywin	Tukey (tapered cosine) window

















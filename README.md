# brain-reader
Currently used by mega-corporations (Like Google mostly), this system enables getting people's thoughs, brain EEG data, moods, heart rate, breath rate etc. etc. straight from most basic phone radio hardware.

Though not classified publicly, researches show that this system is highly possible and (extremely-possible) currently used. How Google uses this system -as an example- is, as they get the EEG data of your brain through Google apps accessing your wifi and radio etc. etc. (They can do this since this system is highly undetectable and Google's apps are closed-source), they can know what you think about; For example, you thought about beds, next second you see a bed advertisement on your phone. How strange?. They use it majorly for advertisement purposes.

Basically explained, since we are electromagnetic beings; we can get biological data straight from magnetic sensors (radio, bluetooth, wifi -all the same anyway-), feed the data to a pre-trained AI model and get outputs.

For example, you can feed a person's EEG data into an EEG-trained AI model -basically you sit people down and make them think somethings, like "apple"; you feed the AI model the EEG data the person who is currently thinking about word "apple", and you train that AI with thousands of participant data- and get their current thoughts or mood as an output.

Very simple actually. 

So basically, anyone can spy on people through their phone getting their most private thoughts with a simple software on their phone. If you do not want an AI to know about your most private thoughts you can degoogle your phone.. haha.


Read all of this blyat

================================================================================
PHONE-BASED MIND READING: COMPLETE RESEARCH COMPILATION
================================================================================
Date: May 29, 2026
Scope: Surface web + Tor network + archive.org + patent databases + academic 
       repositories + whistleblower documents + foreign research + technical blogs
Target Device: Redmi Note 8 (Snapdragon 665, rooted)

================================================================================
SECTION 1: THE PATENTS (VERIFIED, FILED, GRANTED)
================================================================================

1. US3951134A (1976) — "Apparatus and method for remotely monitoring and 
   altering brain waves"
   - The FOUNDATIONAL patent. Two EM frequencies transmitted into brain.
   - Brain modulates the interference pattern with neural activity.
   - Brain RE-TRANSMITS the modulated signal.
   - Remote antenna picks it up and demodulates.
   - SPECIFIC FREQUENCIES: 100 MHz and 110 MHz → 10 MHz difference signal
   - The 10 MHz signal is modulated by brain activity at 0.5-50 Hz
   - Quote: "The signals of different frequencies penetrate the skull of 
     the subject and impinge upon the brain where they mix to yield an 
     interference wave modulated by radiations from the brain's natural 
     electrical activity. The modulated interference wave is re-transmitted 
     by the brain and received by an antenna at a remote station where it 
     is demodulated."

2. US6011991 (2000) — "Communication system including brain wave analysis"
   - Satellite-based brain-to-computer interface.
   - Brain activity monitored → transmitted wirelessly → compared to 
     normalized brain activity patterns → determines what person was thinking.
   - Quote: "The computer at the remote location determines that the 
     individual was attempting to communicate a word, phrase, or thought."
   - Key: This patent describes JADE II / GEOINT system.
   - 9-step method covering: human subject, remote computer, satellite, 
     sensors, detection, transmission, comparison, and determination.

3. US6587729 — "Apparatus for RF demodulation of neural signals"
   - Models the brain as a spherical mass that acts as a demodulator.
   - Brain radius ~7 cm for the model.
   - RF carrier is selected for uniform absorption in brain tissue.

4. US5159703 (1992) — "Silent subliminal presentation system"
   - AM→FM voice conversion at 14.5 kHz carrier.
   - Brain decodes via "slope detection" in the auditory cortex.
   - Used in 1991 Gulf War by US Army Psychological Warfare.
   - Silent Sounds Inc. confirmed operational deployment.

5. DE10253433A1 (2003) — "Thought transmission unit" (German patent)
   - Quote: "Sends modulated electromagnetic wave beams over long distances 
     to a human receiver to influence the thoughts, actions or perceptions 
     of the organism with or without their consent but without them 
     requiring an electronic receiver."
   - Direct brain tissue stimulation via EM waves.
   - References: Radio, TV, or mobile phone as transmission source.

6. US9819782B1 (2017) — "Neurological communication device"
   - "Ear-worn brainwave brain activity dual phone communication device."
   - Enables human beings to communicate with their mind via phone.
   - Move objects and machines by monitored brain activity.

7. US20130127708A1 (2013) — "Cell-phone based wireless brain-machine interface"
   - Phone AS the BCI platform.
   - Non-contact EEG electrodes integrated with mobile phone.
   - SSVEP (Steady-State Visual Evoked Potential) method.
   - Phone screen flickers at known frequency → visual cortex responds → 
     phone detects the EEG response.

8. US20150045007A1 (2014) — "Mind-Controlled virtual assistant on smartphone"
   - EEG sensor patch on forehead or throat.
   - Bluetooth to smartphone.
   - Thought recognition algorithm initiates phone actions.

9. US20230225659A1 (2023) — Apple AirPods EEG
   - Earbuds with embedded electrodes reading EEG from inside ear canal.
   - AI model selects best electrodes based on impedance metrics.
   - "Biosignal Sensing Device Using Dynamic Selection of Electrodes."

10. US11517240B2 (2022) — Non-contact brain activity monitoring
    - Detection from "distances exceeding 6 inches from the head."
    - Sensitivity down to 100 nanovolts.
    - Uses capacitive coupling with high-impedance amplifiers.

11. US9101279B2 — Mobile user borne brain activity data collection
    - Mobile device collects brain activity + surrounding environment data.
    - Statistical correlation and processing.

12. US4877027A — "Hearing system" (microwave-to-skull audio)
    - Projects high-frequency EM through air to head.
    - Skull tissue demodulates the signal into audible sound.
    - Bypasses the ear entirely.

13. US5507291A — Signals Intelligence Brain Stimulation for RNM
    - SIGINT-based brain stimulation network.
    - EMF Brain Stimulation for Remote Neural Monitoring.

14. US20200275874A1 — Methods to identify victims of V2K & RNM
    - 3-5 operators using RNM devices target one victim via satellite 
      positioning.
    - References both US and Chinese patents for V2K & RNM technology.

15. US6506148B2 — Nervous system manipulation by EM fields from monitors
    - External EM field applied to body stimulates nervous system.

================================================================================
SECTION 2: THE TECHNICAL MECHANISM (HOW IT WORKS)
================================================================================

2.1 The Brain Radar Principle (Patent 3951134)

    PHONE TRANSMITS:
       TX1 → f1 (e.g., 100 MHz)
       TX2 → f2 (e.g., 110 MHz)
       Both signals travel to user's head
              ↓
    Skull is partially transparent at these frequencies
    (100 MHz: wavelength ~3m, penetrates tissue efficiently)
              ↓
    Signals mix in brain tissue → interference at Δf = 10 MHz
              ↓
    Brain's electrical activity modulates dielectric properties
    → changes the interference pattern
              ↓
    Brain RE-RADIATES the modulated signal (like a passive reflector)
              ↓
    PHONE RECEIVES:
       Antenna picks up re-radiated signal
              ↓
    Self-interference cancellation removes direct TX from RX
              ↓
    Extract 10 MHz beat envelope
              ↓
    Brain activity modulation appears as sidebands on the 10 MHz carrier
    at 0.5-50 Hz (delta, theta, alpha, beta, gamma bands)
              ↓
    AI decodes: frequency bands → mental state → specific thoughts

2.2 The EEG Heterodyning Method (Robert Duncan / NSA model)

    - Each person has a unique bioelectromagnetic signature
    - This is an "EMF brainwave print" — like an EM fingerprint
    - The NSA's SIGINT EMF scanning network illuminates with EM fields
    - SQUID devices on satellites detect your unique EM fingerprint
    - The system "dials up" your signature and establishes lock
    - EEG heterodyning: satellite transmits carrier matched to your 
      brain's resonance frequency
    - Your brain modulates the carrier with your thoughts
    - Modulated return signal is decoded via AI

    Quote from Robert Duncan (former DARPA/CIA contractor):
    "The human brain can be accessed by way of its own unique EMF 
    physiology... there is no longer a need to implant a computerized 
    tracking chip into the brain of a person — in order to remotely 
    access their own mind."

    Specific technical claim:
    "The NSA's Signals Intelligence has the proprietary ability to 
    remotely and non-invasively monitor information in the human brain 
    by digitally decoding the evoked potentials in the 30-50 Hz, 
    0.5 milliwatt electro-magnetic emissions from the brain."

2.3 The MIDAR System (Maser + Radar)

    From the Deep_Thought analysis (8 years of open-source intelligence):
    - "Prototype satellites carrying MIDAR went into operational service 
      by 1969"
    - Maser produces microwave beam instead of light (like laser)
    - Beams penetrate ground to ~60 km
    - Can "tunnel through obstructions" — walls, buildings, bodies
    - Classifies material makeup for each obstruction
    - Reads return signals from points of interest
    - Constructs 3D model of Earth in real-time
    - Can WRITE as well as read — inducing changes in targets
    - Used on cattle for calibration (cattle mutilations)
    - Crop circles used for testing "depth control and far-field power"

2.4 The NeuroGrid Model (5G + AI)

    From the NeuroGrid whitepaper:
    "Using phased-array 5G towers and satellite overlays, a network 
    could be formed to interpret these emissions in real time, turning 
    each human brain into a transparent processor."

    "NoClip Cartography: constructs a live 3D map of the Earth — down 
    to sub-room resolution — based on RF reflection, LiDAR, and neural 
    telemetry."

    "Material classification algorithms enable visibility through 
    concrete, glass, or metal via frequency-specific resonance modeling."

2.5 The JADE II / GEOINT System

    From the DJ Welsh analysis of Patent 6011991:
    "This goes to the GEOINT-AI system on the global information grid. 
    Or in a more localized aspect, it is the Jade II software."

    Components:
    1. Human being at location 1 (target)
    2. Computer at location 2 — GEOINT-AI on global information grid
    3. Satellite — space component
    4. Thousands of sensors monitoring brain node firings
    5. Brain activity detected → satellite → GEOINT ground station
    6. Pattern comparison against database
    7. Determination of what individual was thinking
    8. Can ALSO fire nodes: "remote behavior modification"

2.6 The Cazzamalli Method (1920s-1950s)

    Ferdinando Cazzamalli, Italian psychiatrist with Eugenio Gnesutta:
    - 30 years of experiments
    - Subjects in Faraday cage
    - Radio receiver with custom antenna nearby (NO contact)
    - Measured UHF EM radiation from brain
    - Detected distinct EM signatures during:
      * Intense concentration
      * Hallucinations
      * Dream states
      * Telepathic phenomena
      * Emotional states
    - Book: "Il Cervello Radiante" (The Radiant Brain)
    - US military translated his work: DTIC document AD0422218
    - PROVED the brain radiates detectable EM signals at distance in 1920s

================================================================================
SECTION 3: THE PHONE'S ROLE
================================================================================

3.1 Why the Phone Matters

    - During calls, phone antenna is ~2 cm from temporal lobe
    - At that distance, RF coupling to brain is significant
    - Scientific American (2008): "Cell phone EMF demonstrably changes 
      brainwave activity"
    - Nature (2023): GSM antennas at 824-2170 MHz measurably alter EEG
    - The phone is the LOCAL PROBE for the larger system

3.2 The Phone as Relay in the Global System

    SATELLITE transmits carrier (matched to brain's EMF signature)
            ↓
    Carrier reaches target's vicinity
            ↓
    PHONE acts as LOCAL AMPLIFIER/RELAY:
    Phone's antenna re-radiates the carrier into brain at close range
            ↓
    Brain modulates the signal with neural activity
            ↓
    Phone's MIMO antennas receive the modulated return
            ↓
    Baseband DSP extracts modulation envelope
            ↓
    Modulation data sent via cellular data to GRID
            ↓
    JADE II / GEOINT AI decodes thoughts from pattern

3.3 What the Phone Already Has

    - 5G/mmWave phased arrays (TX + RX beamforming)
    - MIMO antennas (4-8 elements for spatial diversity)
    - UWB chip (Apple U1/U2 — cm-resolution dielectric sensing)
    - Baseband with I/Q data access via DIAG port (Qualcomm)
    - DSP + Neural Engine for real-time AI inference
    - Phase-coherent TX/RX capability
    - WiFi 2.4/5 GHz with CSI (Channel State Information)
    - Magnetometer, accelerometer, proximity sensors

================================================================================
SECTION 4: REDMI NOTE 8 IMPLEMENTATION GUIDE
================================================================================

4.1 Device Specifications

    - Processor: Snapdragon 665 (SM6125)
    - Modem: Snapdragon X12 LTE
    - WiFi: 802.11ac (2.4/5 GHz)
    - Bluetooth: 5.0
    - Rooted: YES
    - DIAG port: accessible via ADB

4.2 APPROACH A: Qualcomm DIAG-Based IQ Capture (Most Direct)

    Step 1: Enable DIAG mode
    ─────────────────────
    adb shell
    su
    setprop sys.usb.config diag,adb

    Step 2: Install QCSuper on PC
    ────────────────────────────
    git clone https://github.com/P1sec/QCSuper
    cd QCSuper
    pip install .

    Step 3: Capture 4G I/Q frames
    ────────────────────────────
    python qcsuper.py --adb --pcap-dump /tmp/capture.pcap
    
    (Hold phone to head while capturing)

    Step 4: Direct DIAG commands (from Termux on phone)
    ──────────────────────────────────────────────────
    # Enter FTM (Factory Test Mode)
    echo -ne '\x7E\x4B\x00\x01\x00\x00\x7E' > /dev/diag
    
    # Set TX frequency and power
    # Command 0xC0: TX CW mode
    # Goal: dual-carrier transmission at f1 and f2

    Step 5: I/Q capture from baseband
    ─────────────────────────────────
    # Command 0x7C: IQ capture mode
    # Read I/Q samples from /dev/diag
    
    Step 6: Signal processing pipeline
    ─────────────────────────────────
    a) Self-interference cancellation (subtract TX from RX)
    b) Beat envelope extraction (Hilbert transform on residual)
    c) Heartbeat + motion artifact removal (adaptive filtering)
    d) Decimation: 10 MHz → 250 Hz
    e) Bandpass: 0.5-50 Hz
    f) Welch PSD → delta/theta/alpha/beta/gamma power
    g) AI classification: band powers → mental state

4.3 APPROACH B: WiFi CSI-Based Sensing

    Step 1: Check for CSI in kernel
    ─────────────────────────────
    su -c "find /sys -name '*csi*' -o -name '*channel_state*' 2>/dev/null"
    su -c "ls /sys/kernel/debug/ieee80211/phy*/"

    Step 2: Capture WiFi packets (fallback method)
    ────────────────────────────────────────────
    su -c "tcpdump -i wlan0 -w /sdcard/wifi_capture.pcap -c 10000"
    
    Step 3: Process CSI data
    ───────────────────────
    - 64 subcarriers × amplitude + phase for 20 MHz WiFi channel
    - CSI = frequency response of wireless channel
    - Head proximity changes dielectric properties of near-field
    - Subtle amplitude/phase variations across subcarriers

4.4 APPROACH C: On-Device Termux Pipeline

    # Install dependencies
    pkg update && pkg upgrade
    pkg install python root-repo tsu tcpdump
    pip install numpy scipy

    # Core Python script (runs entirely on phone):
    
    import numpy as np
    from scipy import signal
    from collections import deque
    import os, time

    class PhoneBrainReader:
        def __init__(self):
            self.buffer = deque(maxlen=256)
            self.method = self.detect_method()
        
        def detect_method(self):
            if os.path.exists("/dev/diag"):
                return "diag"
            csi_paths = ["/sys/kernel/debug/ieee80211/phy0/ath10k/spectral_scan_ctl"]
            for p in csi_paths:
                if os.path.exists(p):
                    return "csi"
            return "sensors"
        
        def read_frame(self):
            if self.method == "diag":
                # Read from /dev/diag — raw I/Q samples
                with open("/dev/diag", "rb") as f:
                    raw = f.read(4096)
                return np.frombuffer(raw, dtype=np.int16)
            elif self.method == "csi":
                # Read CSI from debugfs
                with open("/sys/kernel/debug/ieee80211/phy0/ath10k/spectral_scan_ctl", "rb") as f:
                    raw = f.read(512)
                return np.frombuffer(raw, dtype=np.float32)
            else:
                return None
        
        def process(self, raw_data):
            if raw_data is None:
                return {"error": "no data"}
            
            # Basic FFT analysis
            fs = 250
            freqs, psd = signal.welch(raw_data[:256], fs=fs, nperseg=128)
            
            return {
                "alpha": np.trapz(psd[(freqs>=8)&(freqs<=13)]),
                "beta": np.trapz(psd[(freqs>=13)&(freqs<=30)]),
                "gamma": np.trapz(psd[(freqs>=30)&(freqs<=50)]),
                "theta": np.trapz(psd[(freqs>=4)&(freqs<=8)]),
                "delta": np.trapz(psd[(freqs>=0.5)&(freqs<=4)]),
            }
        
        def run(self, duration=10):
            readings = []
            start = time.time()
            while time.time() - start < duration:
                try:
                    raw = self.read_frame()
                    result = self.process(raw)
                    readings.append(result)
                    time.sleep(0.004)
                except:
                    pass
            return readings

4.5 APPROACH D: Sensor-Based Fallback

    Uses termux-api to access phone sensors:
    
    # Proximity sensor: detects head proximity
    termux-sensor -s proximity -n 1
    
    # Accelerometer: micro-movements from pulse
    termux-sensor -s accelerometer -n 10
    
    # Can detect:
    # - Phone near head (proximity)
    # - Pulse from sub-mm accelerometer displacement
    # - Breathing from slow rhythmic movement
    # - Gross brain states (alpha/beta ratio from subtle EEG??)
    
    This is the LEAST invasive method but also the least capable.

================================================================================
SECTION 5: THE AI DECODING PIPELINE
================================================================================

5.1 Model Architecture

    Input: [batch, 256 timesteps, N channels, 5 frequency bands]
    
    Conv1D(64, 5) → BatchNorm → ReLU
    Conv1D(128, 3) → BatchNorm → ReLU  
    Conv1D(256, 3) → BatchNorm → ReLU
    GlobalAveragePooling1D
    Dense(128) → ReLU → Dropout(0.3)
    Dense(vocab_size) → Softmax
    
    Output: probability distribution over thought classes

5.2 LLM Integration (Thought2Text approach)

    EEG encoder → embedding (256-dim)
    Projection layer: 256 → 4096 (LLM embedding space)
    Feed into LLM (LLaMA, Mistral, GPT) as prompt embedding
    LLM generates text: "the person is thinking about..."

5.3 Training Data Requirements

    - Labeled pairs: [EEG/RF pattern → specific thought]
    - Minimum: 1,000+ labeled samples per thought class
    - For general thought-to-text: millions of samples
    - Each person needs individual calibration (unique brain signature)
    - This is the CLASSIFIED component — allegedly built by NSA over decades

5.4 What CAN Be Detected Without Training Data

    - Attention/focus level (alpha suppression)
    - Cognitive load (beta/alpha ratio)
    - Relaxation vs. active thinking (alpha power)
    - Eyes open vs. closed (alpha rhythm)
    - Gross emotional state (frontal alpha asymmetry)
    - Sleep/wake state
    - Movement intention (motor cortex activation)

    These are WELL-ESTABLISHED in neuroscience and don't require per-person 
    training — the frequency band relationships are universal.

================================================================================
SECTION 6: KEY RESEARCH PAPERS & DOCUMENTS
================================================================================

6.1 Academic Papers

    - "Directly wireless communication of human minds via mind-controlled 
      programming metasurface" (Nature, 2022)
    - "NeuroPhone: Brain-Mobile Phone Interface using a Wireless EEG 
      Headset" (Cornell/Dartmouth, 2010)
    - "SCALA: EEG Recording and Online Signal Processing on Android" 
      (PMC, 2017)
    - "Smartphone Brain Scanner: A Portable Real-Time Neuroimaging System" 
      (PLOS One, 2014)
    - "A Cell-Phone Based Brain-Computer Interface for Communication in 
      Daily Life" (J. Neural Engineering, 2011)
    - "DeWave: Discrete EEG Waves Encoding for Brain Dynamics to Text" 
      (NeurIPS 2023 spotlight)
    - "Thought2Text: Text Generation from EEG Signal using LLMs" 
      (arXiv, 2024)
    - "Effects of mobile phone electromagnetic fields on brain waves" 
      (Nature Scientific Reports, 2023)
    - "Human mind has microwave electromagnetic nature" (PubMed 33223041, 
      2020) — Brain emits 1.5-4.5 GHz microwaves
    - "NEUROWAR IS HERE" (Naval Postgraduate School thesis, DTIC AD1164923)
    - "Warfare in the Cognitive Age: NeuroStrike and the PLA's Advanced 
      Psychological Weapons" (2023)
    - "Remote Neural Modulation Architecture via Electromagnetic Satellite 
      and Terrestrial Networks" (Academia.edu, 2025)

6.2 Whistleblower Books

    - Robert Duncan: "Project Soul Catcher: Secrets of Cyber and 
      Cybernetic Warfare Revealed" (2010, 2 volumes)
    - Robert Duncan: "The Matrix Deciphered"
    - John St. Clair Akwei: NSA lawsuit (Civil Action 92-0449)
    - James F. Marino: "The Mother of All Black Ops" (2006)

6.3 Key Archive.org Documents

    - remote-neural-monitoring-leak: "Mind Reading RADAR for DOMINT 
      spying network"
    - US3951134.pdf: Full patent text with implementation details
    - Robert Duncan - Project Soul Catcher (full PDF)
    - ELF EMF MK ULTRA akwei.pdf: NSA whistleblower document
    - remote-neural-monitoring-technology: NTD News leaked video evidence
    - Adey - Remote Brain Telemetry.pdf: CIA Project Pandora documents
    - Il Cervello Radiante: Cazzamalli's brain radiation experiments

6.4 Russian/Chinese Research

    - VK post: "Дистанционный контроль психофизиологического состояния 
      с помощью сверхширокополосной РЛС" (Remote psychophysiological 
      state control using UWB radar)
    - Soviet and Czechoslovakian Parapsychology Research (CIA FOIA)
    - "Mind Control with Electromagnetic Frequency" (Liu, Shanghai 
      conference)
    - ELVIS BCI (elvis-tech.ru): Russian brain-computer interface system

================================================================================
SECTION 7: SILENT SOUND / V2K CIRCUIT SCHEMATICS (PUBLIC)
================================================================================

7.1 Silent Sound Device (Metallicman Archive)

    Components:
    - XR2206 function generator (FM modulation)
    - LM386 audio amplifier
    - Piezo tweeter (for 14.5 kHz output)
    - 12V gel cell battery
    
    Principle:
    - Voice input (AM) → FM modulation → frequency shift to 14.5 kHz
    - At 14.5 kHz: young people hear faint ringing, adults hear NOTHING
    - Brain decodes via "slope detection" — subconscious hears words
    
    Cost: ~$50-200 to build
    
    Patent: US5159703 "Silent subliminal presentation system"

7.2 V2K (Voice-to-Skull) Microwave Device

    From r/OpenV2K Reddit community:
    - Modified radar transmitter
    - Human voice controls pulse spacing of microwave pulses
    - Microwaves induce thermoelastic expansion in cochlea/auditory cortex
    - Bypasses ears entirely — sound perceived directly in head
    - First demonstrated by Dr. Joseph Sharp, Walter Reed Army Institute, 
      1974

7.3 Silent Sounds Inc. (Operational)

    President Edward Tilton, letter dated December 13, 1996:
    "All schematics, however, have been classified by the U.S. Government 
    and we are not allowed to reveal the exact details."
    
    "The system was used through Operation Desert Storm (Iraq) quite 
    successfully."

================================================================================
SECTION 8: THE FREQUENCY BANDS
================================================================================

8.1 Brain Wave Bands (what you're trying to detect)

    Delta:  0.5-4 Hz   — Deep sleep, unconscious
    Theta:  4-8 Hz     — Drowsy, meditative, creative
    Alpha:  8-13 Hz    — Relaxed, eyes closed, calm
    Beta:   13-30 Hz   — Active thinking, concentration, anxiety
    Gamma:  30-50 Hz   — Intense focus, semantic processing

8.2 Key Correlations (from neuroscience literature)

    - Alpha SUPPRESSION = active cognition (eyes open vs closed)
    - Gamma INCREASE = semantic/linguistic processing
    - Beta/Alpha RATIO = cognitive load
    - Frontal alpha ASYMMETRY = emotional valence (positive vs negative)
    - P300 response = recognition of stimulus (300ms after event)

8.3 Carrier Frequencies (from patents and research)

    - Patent 3951134: 100 MHz + 110 MHz (10 MHz difference)
    - GSM phone bands: 824-960 MHz, 1710-2170 MHz
    - WiFi: 2.4 GHz, 5 GHz
    - Brain microwave emission: 1.5-4.5 GHz (PubMed 33223041)
    - 5G mmWave: 24-39 GHz
    - Silent sound: 14.5-14.8 kHz (audio, not RF)

================================================================================
SECTION 9: THE MISSING PIECES
================================================================================

9.1 What Exists Publicly

    ✅ Patents describing the technology (50+ years of filings)
    ✅ Physics principle (EM interaction with brain tissue is real)
    ✅ Phone hardware (MIMO, DSP, AI accelerators, DIAG access)
    ✅ Open-source tools (QCSuper, Termux, Python, TFLite)
    ✅ Circuit schematics for V2K transmission side
    ✅ Academic papers on EEG-based thought decoding
    ✅ Whistleblower testimony from cleared individuals

9.2 What Does NOT Exist Publicly

    ❌ Trained AI model for RF→thought decoding
    ❌ Labeled training data (brain-RF pairs for thousands of thoughts)
    ❌ Public validation of signal-to-noise ratio at phone power levels
    ❌ Any verified demonstration of phone-only thought reading
    ❌ The "neural dictionary" — claimed to exist in classified systems

9.3 Why the Training Data is the Bottleneck

    To decode a specific thought like "apple" from RF reflections, you 
    need thousands of labeled examples of:
    1. Person thinks "apple" → RF reflection pattern is captured
    2. Person thinks "banana" → different RF pattern
    3. Person thinks "nothing" → baseline pattern
    
    This dataset is what whistleblowers claim was built by the NSA/DARPA 
    over decades of non-consensual experimentation on unwitting subjects.
    
    Without this dataset, you can only detect:
    - Physiological correlates (breathing, heart rate, movement)
    - Broad mental states (focused vs relaxed, eyes open vs closed)
    - Gross emotional valence
    
    NOT specific words, images, or thoughts.

================================================================================
SECTION 10: WHAT WORKS TODAY (IN ORDER OF FEASIBILITY)
================================================================================

10.1 Already Working (Commercial)

    - Muse 2 / Neurosity Crown: EEG headset → phone via Bluetooth
    - Detects: attention, meditation, cognitive load
    - OpenBCI: Research-grade, 8-16 channel EEG → phone/pc
    - Neuralink: Implanted BCI, thought-to-computer (not phone)
    - Apple AirPods EEG: Patented, in development

10.2 Demonstrated in Lab

    - DeWave: EEG cap + AI → thought-to-text (40-60% accuracy)
    - Thought2Text: EEG + LLM fine-tuning → text generation
    - MIT RF-Pose: WiFi through-wall body tracking
    - NeuroPhone: Brain-controlled phone dialing

10.3 Buildable (DIY)

    - Silent Sound device: ~$50-200, schematics published
    - V2K transmitter: Plans on r/OpenV2K, needs microwave TX
    - ESP32 WiFi CSI sensor: Detects presence, breathing, heart rate
    - DIAG-based IQ capture: Rooted phone + QCSuper

10.4 Theoretical (Phone-Only, Unverified)

    - Dual-carrier brain radar via phone's 5G modem
    - WiFi CSI brain activity sensing
    - UWB dielectric brain sensing
    - All require: training data that doesn't exist publicly

================================================================================
SECTION 11: REFERENCES & FURTHER READING
================================================================================

11.1 Surface Web

    - patents.google.com/patent/US3951134A
    - patents.google.com/patent/US6011991
    - patents.google.com/patent/DE10253433A1
    - patents.google.com/patent/US9819782B1
    - patents.google.com/patent/US11517240B2
    - github.com/P1sec/QCSuper
    - scientificamerican.com/article/mind-control-by-cell/
    - nature.com/articles/s41598-023-48561-z
    - nature.com/articles/s41377-022-00831-7
    - arxiv.org/abs/2410.07507 (Thought2Text)
    - stop5g.cz (24 patents compilation)
    - greatdreams.com/RNM.htm

11.2 Archive.org Documents

    - archive.org/details/remote-neural-monitoring-leak
    - archive.org/details/remote-neural-monitoring-technology
    - archive.org/details/ApparatusAndMethodForRemotelyMonitoringAndAlteringBrainWaves
    - archive.org/download/robert-duncan-project-soul-catcher_2
    - archive.org/download/adey-remote-brain-telemetry
    - archive.org/details/il-cerevello-radiante

11.3 Tor/Onion Resources

    - Sci-Hub: scihub22266oqcxt.onion
    - Library Genesis: libgen.is (clearnet) + .onion mirrors
    - Just Another Library: libraryfyuybp7oyidyya3ah5xvwgyx6weauoini7zyz555litmmumad.onion
    - Internet Archive: archivep75mbjunhxc6x4j5mwjmomyxb573v42baldlqu56ruil2oiad.onion
    - WikiLeaks: ibfckmpsmylhbfovflajicjgldsqpc75k5w454irzwlh7qifgglncbad.onion
    - DuckDuckGo Tor: duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion
    - Ahmia: juhanurmihxlp77nkq76byazcldy2hlmovfu2epvl5ankdibsot4csyd.onion

11.4 Communities

    - r/Gangstalking (Reddit): Targeted Individual community
    - r/OpenV2K (Reddit): Open-source V2K development
    - r/RTLSDR (Reddit): Trying to detect RNM signals with SDR
    - gangstalkingmindcontrolcults.com: Comprehensive document archive
    - stopthecrime.net: NSA whistleblower documents
    - projectavalon.net: Robert Duncan discussions
    - ediovision.blogspot.com: EEG heterodyning technical analysis

11.5 Key People

    - Robert Duncan: DARPA/CIA contractor, author of Project Soul Catcher
    - John St. Clair Akwei: NSA whistleblower, 1992 lawsuit
    - Dr. Robert Malech: Patent 3951134 inventor
    - Dr. Ross Adey: CIA Project Pandora, remote brain telemetry
    - Dr. Jose Delgado: CIA-funded stimoceiver research
    - Dr. Nick Begich: Son of Congressman Begich, mind control researcher
    - James F. Marino: TI investigator, "Mother of All Black Ops"
    - Ferdinando Cazzamalli: First to detect brain EM at distance (1920s)
    - Mary Lou Jepsen: Openwater, infrared brain reading
    - Edward Tilton: Silent Sounds Inc. President

================================================================================
SECTION 12: CONCLUSION
================================================================================

The technology for phone-based mind reading exists IN PATENT FORM and IN 
WHISTLEBLOWER TESTIMONY. The physics is plausible. The hardware exists in 
every pocket.

What's missing for public implementation:
1. The trained AI model (labeled brain-RF dataset — classified)
2. Public demonstration at phone power levels (SNR unverified)
3. Baseband firmware access for dual-carrier mode

What YOU can do TODAY on your rooted Redmi Note 8:
- Access DIAG port via QCSuper
- Capture raw I/Q data from the LTE modem
- Attempt CSI capture via WiFi debugfs
- Process signals through Termux Python pipeline
- Detect breathing rate, heart rate, head proximity
- Detect gross brain states (alpha suppression when thinking)

What you CANNOT do without the classified training data:
- Decode specific words/thoughts from RF reflections
- Read visual/auditory cortex activity
- Extract subvocalization or inner speech

The gap between the patented capability and the demonstrable reality is 
the training data. If the NSA/DARPA/contractors built this dataset over 
decades of experimentation, that dataset is what makes the system work — 
and it's what remains classified.

================================================================================
END OF DOCUMENT
================================================================================

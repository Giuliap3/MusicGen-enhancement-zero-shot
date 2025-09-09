# MusicGen-enhancement-zero-shot
Pipeline per restauro audio MusicGen: approcci DSP vs DSP+Demucs

Questo progetto affronta il miglioramento della qualità audio nei campioni generati da MusicGen attraverso due pipeline: 
* un approccio puramente tradizionale basato su funzioni DSP
* un metodo ibrido che combina la separazione delle sorgenti mediante Demucs e un post-processing DSP

# Installazione

```bash
git clone https://github.com/your-username/MusicGen-Audio-Restoration.git
cd MusicGen-Audio-Restoration
pip install -r requirements.txt

torch>=2.0.0
torchaudio>=2.0.0
librosa>=0.10.0
soundfile>=0.12.1
matplotlib>=3.7.0
seaborn>=0.12.2
numpy>=1.24.0
scipy>=1.10.0
noisereduce>=1.0.0
demucs>=6.0.0
pyloudnorm>=0.1.0
pydub>=0.25.1
tqdm>=4.65.0
transformers>=4.30.0
ipython>=8.12.0
pandas>=2.0.0

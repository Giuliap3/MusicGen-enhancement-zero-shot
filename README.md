# MusicGen-enhancement-zero-shot
Pipeline per restauro audio __MusicGen__: approcci DSP vs Demucs+DSP
## 👩‍💻 Autore: Giulia Pontesilli
Questo progetto affronta il miglioramento della qualità audio nei campioni generati da MusicGen attraverso due pipeline: 
* un approccio puramente tradizionale __DSP__ 💻: uso di funzioni e algoritmi matematici, senza modelli preaddestrati di ML 
* un approccio ibrido che combina il modello preaddestrato __Demucs + un post-processing DSP__ 💻🤖: Demucs separa le sorgenti (drums, bass e other), queste ultime vengono sottoposte a un post-processing mirato e poi unite in modo bilanciato attraverso dei pesi

## 📁 Repository Structure

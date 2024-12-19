# RecuVol
TUS-REC Challenge | MICCAI 2024 | Submission

This repository contains code and scripts for reconstructing a 3D ultrasound (US) volume from freehand 2D US image sequences without the need for external tracking devices. The approach leverages a combination of a CNN-based feature extractor (ResNet) and an LSTM-based temporal model to predict consecutive frame-to-frame rigid transformations. These transformations are then accumulated to form a global trajectory, which can be used to generate a dense displacement field (DDF) for 3D volume reconstruction.

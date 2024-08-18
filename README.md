
# WhisperX Speaker Diarization

This project implements speaker diarization using the `WhisperX` library. Speaker diarization involves partitioning an audio stream into homogeneous segments according to the speaker identity. This is useful for applications such as transcriptions, where distinguishing between different speakers in an audio file is necessary.

## Project Overview

The goal of this project is to create a tool that can automatically identify and segment different speakers in an audio file. By leveraging the capabilities of the `WhisperX` library, the project delivers high-accuracy speaker diarization, making it suitable for various applications in media, transcription services, and more.

## Key Features

- **Automatic Speaker Segmentation**: Identifies different speakers in an audio recording.
- **High Accuracy**: Utilizes advanced machine learning models provided by the `WhisperX` library.
- **Ease of Use**: Designed to be simple to set up and run within a Jupyter Notebook environment.

## Workflow

1. **Audio Input**: Prepare and load the audio file that you want to process.
2. **Diarization Process**: The notebook processes the audio, segmenting it based on speaker identities.
3. **Output**: The result is a segmented audio file or data that labels sections of the audio by speaker.

## How to Clone the Project

To clone and set up the project:

1. **Clone the repository**:
  
   git clone https://github.com/majidhanif230/Speech_Diarization_using_WhisperX
   cd Speech_Diarization_using_WhisperX
 
2. **Run the Jupyter Notebook**:

   type jupyter notebook in cmd

3. **Open and execute** the `WhisperX_Speaker_Diarization.ipynb` file to start processing your audio files.

## Future Aspects

Potential future enhancements include:

- **Real-time Diarization**: Implementing a real-time processing capability for live audio streams.
- **Improved Accuracy**: Incorporating more advanced models or fine-tuning existing ones to improve accuracy.
- **Integration with Transcription Services**: Automatically generating transcriptions alongside speaker labels.

## Acknowledgements

This project was developed by Majid Hanif as part of an assignment for **Machine Learning 1 Pvt Ltd**. It utilizes the `WhisperX` library for speaker diarization. Special thanks to the **Prompt Engineering YouTube channel** for providing valuable resources and insights.

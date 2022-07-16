# voice_assitent2
import speech_recognition

sr = speech_recognition.Recognizer()
sr.pause_threshold = 0.5


def greeting():
    return 'Здраствуй'


def listen_comand():
    pass

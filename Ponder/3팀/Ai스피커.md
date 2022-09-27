# 인공지능 스피커

## 파이썬 설정


### Windows 가상환경 설치

```
python -m venv myenv
```

가상환경 활성화
```
.\myenv\Scripts\activate
```

```
pip install playsound==1.2.2
```



```
pip install SpeechRecognition
```
```
Pip install PyAudio
```

### mac 가상환경 설치

```
python3 -m venv myenv
```

가상환경 활성화
```
source myenv/bin/activate
```
```
pip3 install gTTS
```
```
pip3 install playsound
```
```
pip3 install PyObjC
```

([홈브로](https://eunhee-programming.tistory.com/259)가 설치되어 있어야함)

```
pip3 install SpeechRecognition
```
```
brew install portaudio
```
파일 만들기
```
sudo nano $HOME/.pydistutils.cfg
```
파일 위치 찾기
```
pwd
cd /opt
ls
cd homebrew
ls
cd Cellar 
ls
cd portaudio 
ls
cd 19.7.0 
ls
pwd
```
include
lib
위 두개 파일 링크 확인

파일안에 입력
```
[build_ext]
include_dirs=/opt/homebrew/Cellar/portaudio/19.7.0/include/
library_dirs=/opt/homebrew/Cellar/portaudio/19.7.0/lib/
```
```
pip3 install PyAudio
```
위치 플랫입력후
```
which flac
```
경로가 없을 경우 인스톨 플렛 입력 
```
brew install flac
```

### 23.11.23
Whister realtime работает совсем не realtime, Расшифровка с задержкой 1-2 предложения, нет преимуществ перед обычным.
Буду чекать голос сдающего с помощью чего-то из этого:

https://huggingface.co/pyannote/segmentation

https://huggingface.co/pyannote/segmentation-3.0

https://huggingface.co/pyannote/brouhaha

https://huggingface.co/philschmid/pyannote-segmentation

https://huggingface.co/pyannote/embedding

https://huggingface.co/philschmid/pyannote-speaker-diarization-endpoint

Делать аудиофрагменты на те, когда говорит сдающий, и когда говорит не сдающий.

Когда кто-либо перестаёт говорить, или говорит слишком долго, толкать в whisper

Если вопрошающий закончил говорить, и не начал к моменту расшифровки, пихать в gpt.

По окончанию обрабоки выводить результат
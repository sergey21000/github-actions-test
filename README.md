
> [!WARNING]
> Необходимо именно копировать а не перемещать файлы в директорию `ocr_input`, так как после OCR файлы будут удалены из нее (даже если процесс OCR выполнился неудачно)

> [!INFO]
> Если при запуске контейнер `paddleocr-vlm-server` пишет ошибку `RuntimeError: Unsupported GPU architecture` - изменить тег образа в файле `.env` в переменной `VLM_IMAGE_TAG_SUFFIX`
 - `latest-nvidia-gpu-sm120-offline` для видеокарт архитектуры Blackwell
 - `latest-nvidia-gpu-offline` для видеокарт архитектур, отличных от Blackwell


# Fooocus_extend
Extender for Fooocus

(Any borrowing of code without attribution and permission of the author is considered plagiarism and disrespect for the author).

(Любые заимствования кода без указания авторства и разрешения автора считается плагиатом и неуважением к автору)


<a href="https://colab.research.google.com/github/shaitanzx/Fooocus_extend/blob/main/Fooocus_extend.ipynb" rel="nofollow"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg"></a>


![image](https://github.com/shaitanzx/Fooocus_extend/assets/162459965/c8fabbdf-c93a-4fbe-83c3-8a320dfe2653)
![image](https://github.com/shaitanzx/Fooocus_extend/assets/162459965/538c5054-dab5-4b8d-a3a4-55af11017ece)
![image](https://github.com/shaitanzx/Fooocus_extend/assets/162459965/cc30d308-e63c-4c73-b798-6a65875693db)
![image](https://github.com/shaitanzx/Fooocus_extend/assets/162459965/92e1bec7-4227-47bc-a3f9-e1274dd3d6e6)







Startup order
1. Select a profile
2. Select a theme (light, dark)
3. Memory_patch – reduces consumed video memory, which prevents errors when using various ImagePrompt modes
4. GoogleDrive_output – enable saving of all generation results to your Google Drive
5. Prompt_translate – enabling an online translator allows you to enter a prompt in any language. Before starting generation, he translates the prompt into English and transmits it to Fooocus
6. Launch colab

Prompt Translate
1. Enable Translate - enable the extension
2. Translate - translation of the prompt into English without starting generation
3. Auto translate "Prompt and Negative prompt" before Generate - enable automatic translation of positive and negative prompts into English before generation
4. See translated prompts after click Generate - show translations of prompts after generation is completed

Model Dowloader
1. CivitAI_API_KEY - required for downloading models from civitai.com It is best to use your personal key, not a third-party one, since if necessary, you can always view ONLY YOUR download history on the site. To do this, you need to register on the website civitai.com and then in the settings you can get the key.
2. Checkpoint Link – adding links to models from civitai.com. If you need to load several models, links to them can be specified separated by commas (,) without spaces
3. Lora Link - adding links to Lora from the site civitai.com. If you need to download several Loras, links to them can be specified separated by commas (,) without spaces.
4. Embedding Link - adding links to Embedding from the site civitai.com. If you need to download several Loras, links to them can be specified separated by commas (,) without spaces.
5. Start Download - start downloading all files via links
6. If CivitAI_API_KEY is absent, then the download not started
7. After downloading all the files, in the Model tab in Advanced mode, you need to update the list of models (click Refresh All Files)
8. To apply Embedding, in the prompt field use a record like (embedding:file_name:1.1)

Порядок запуска
1.	Выбрать профиль
2.	Выбрать тему (светлая, темная)
3.	Memory_patch – уменьшает потребляемую видеопамять, что не позволяет вывалиться в ошибку при использовании различных режимов ImagePrompt
4.	GoogleDrive_output – включение сохранения всех результатов генераций на свой гуглдиск
5.	Prompt_translate – включение онлайн переводчика позволяет вводить промпт на любом языке. Он перед началом генерации переводит промпт на английский язык и передает его в Fooocus
6.	Запустить колаб

Prompt Translate
1. Enable Translate - включение расширения
2. Translate - перевод промпта на англйский язык без запуска генерации
3. Auto translate "Prompt and Negative prompt" before Generate - включение автоматического перевода положительного и отрицательного промптов на английский язык перед генерацией
4. See translated prompts after click Generate - показывать переводы промптов после выполнения генерации

Model Dowloader
1.	CivitAI_API_KEY – необходим для загрузки моделей с civitai.com  Лучше всего использовать свой личный ключ, а не сторонний, так как в случае необходимости на сайте всегда можно посмотреть ТОЛЬКО СВОЮ историю загрузок. Для этого необходимо зарегистрироваться на сайте civitai.com и далее в настройках можно получить ключ.
2.	Checkpoint Link – добавление ссылок на модели с сайта civitai.com. При необходимости загрузки нескольких моделей, ссылки на них можно указывать через запятую (,) без пробелов
3.	Lora Link - добавление ссылок на Lora с сайта civitai.com. При необходимости загрузки нескольких Lora, ссылки на них можно указывать через запятую (,)  без пробелов.
4.	Embedding Link - добавление ссылок на Embedding с сайта civitai.com. При необходимости загрузки нескольких Lora, ссылки на них можно указывать через запятую (,)  без пробелов.
5.	Start Download - запуск скачивание всех файлов по ссылкам
6.	Если отстутсвует CivitAI_API_KEY, то загрузка производиться не будет
7.	После загрузки всех файлов, во вкладке Model в режиме Advanced, необходимо обновить список моделей (нажать Refresh All Files) 
8.	Для применения embedding, в поле промпта используйте запись типа (embedding:file_name:1.1)

Change log

V2 (current version)
1. Added a Model Downloader to Fooocus webui instead of colab

V1
1. added the ability to download models from the civitai.com
2. saving the generated image to Google Drive
3. added prompt translator
4. added a patch for the ability to work in free colab mode 

https://github.com/Griggorii/Android-Anbox.deb/tree/master/data/desktop my idea copy paste /usr/share/xsessions

Что бы скомпилировать оригинал gmock.zip  https://github.com/Griggorii/Android-Anbox.deb/blob/master/gmock.zip распаковывается и кладётся прямо в папку исходного кода или директорий build или как вы её назовёте не важно без него ни как (это я додумал и это получается додумать следовательно это мой патент) сам оригинал git clone https://github.com/anbox/anbox.git 

sudo apt install build-essential cmake cmake-data debhelper dbus google-mock \
    libboost-dev libboost-filesystem-dev libboost-log-dev libboost-iostreams-dev \
    libboost-program-options-dev libboost-system-dev libboost-test-dev \
    libboost-thread-dev libcap-dev libsystemd-dev libegl1-mesa-dev \
    libgles2-mesa-dev libglm-dev libgtest-dev liblxc1 \
    libproperties-cpp-dev libprotobuf-dev libsdl2-dev libsdl2-image-dev lxc-dev \
    pkg-config protobuf-compiler 

cmake . && make 

sudo make install

Дальше дело перепись ярлыков запуска и портирование андроид окружения на линукс что бы воспроизводить apk без костылей

Рекомендую делать всё это на OS 8.0 цветовой диапазон там шире и аналогов на которые я бы хотел перейти я так и не нашёл не на одном сайте мира , потом OS 8.0 стабильна на 200% не каких резкий зависаний итд. Т.е используя мою ось можно получить андроид который будет сверх стабильный и на новейшем ядре

Deb package https://www19.zippyshare.com/v/6e40P9fo/file.html

Данная ОС отдаётся в фонд мозилы потому что нынче гугл прибит гвоздями , а то системд системд все говорят , а не видят суслика.

Гугл гигант итак гребёт с поисковика и маркета , а нового нету ничего только тащат в свою нору наработки.

Вот конфиг firefox https://github.com/Griggorii/linux-firefox-config

Android это не гугл android это OS и не разу не Chrome OS

Я два года работал над OS https://github.com/Griggorii/Cinnamon-Budgie-OS-4.0-beta-based-18.04 что бы она выглядела , а не существовала , гибкий системд на моей OS наоборот не прибит и вы можете отцепить его мне он нужен для systemback и ещё для пары приложенений без вопросов иначе дамп моей ОС прошивки не снять , как отгвоздить с помощью этого ядра https://github.com/Griggorii/linux-image-4.20.8 думаю некоторые знают , но мне д нужен для работы.



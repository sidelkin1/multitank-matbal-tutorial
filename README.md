# multitank-matbal-tutorial

Предназначен для лучшего понимания устройства и работы пакета [MultiTankMaterialBalance](https://github.com/sidelkin1/MultiTankMaterialBalance.jl).

## Быстрая установка

Для работы требуется установка `Jupyter`. Проще всего это сделать, установив [Anaconda](https://www.anaconda.com/), следующим образом:

- Скачайте программу для установки (https://www.anaconda.com/download/) и следуйте инструкции для вашей платформы.

- После установки поставьте галочку для добавления `Python` в переменную среды `PATH`.

Кроме того, должны быть установлены [Julia](http://julialang.org/downloads/) и [Git Bash](https://git-scm.com/downloads). Далее требуется

- Скачать CLI репозиторий с помощью команды 

```
git clone https://github.com/sidelkin1/multitank-matbal-tutorial
```

- Запустить `Julia REPL` и выполнить команду

```julia
using Pkg; Pkg.add("IJulia")
```

- Затем выполнить команду 
 
```julia
pwd("path/to/multitank-matbal-tutorial")
```

где требуется указать правильный путь к скачанному репозиторию

- Установить дополнительно требуемые пакеты через `Julia REPL` с помощью команды
 
```julia
Pkg.activate("."); Pkg.instantiate()
```

- Выполнить в терминале команду

```
jupyter lab path/to/multitank-matbal-tutorial
```

- В папке `tutorial` открыть тетрадку `tutorial.ipynb`
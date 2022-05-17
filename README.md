# Компилятор
Если вы на Windows, то предлагается поставить компилятор от VS, это займёт 5 Gb места на жёстком диске. Но есть альтернатива. Напишите в cmd или В Power Shell
<code>
rustup toolchain install stable-x86_64-pc-windows-gnu
</code>
Затем назначьте его по умолчанию
<code>
rustup default stable-x86_64-pc-windows-gnu
</code>

# Обновление
Проверьте номер версии
<code>
rustc --version
</code>

Обновляется командой
<code>
rustup update stable
</code>

# Запуск программы
<code>
cargo new hello-rust
</code>
Cоздаст необходимую структуру по умолчанию </br>

<code>
cargo run
</code>
Запуск и исполнение в терминале, также будет создан исполняемый файл</br>

Build просто создает исполняемый файл.
<code>
cargo build
</code>

Программу можно запустить без Cargo.toml, для этого перейдите в терминале в директорию, где есть файл rs и напишите 
<code>
rustc file.rs
</code>
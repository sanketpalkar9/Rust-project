<h1>File compressor using Rust</h1>


This Rust program compresses a file using gzip compression. It does the following:

-Checks if the number of command-line arguments is 3 (program name, source file, target file) and exits if not.<br>
-Opens the source file and creates a buffered reader for it.<br>
-Creates the target file and a gzip encoder to compress data into this file.<br>
-Copies the contents of the source file into the encoder, compressing it, and records the time taken for this operation.<br>
-Prints the lengths of the source and compressed files, along with the elapsed time for the compression.<br>

<br>
<h1>What to do?</h1>

<h3>Download Rust and cargo</h3>

write cargo new project1 in terminal

<h3>in cargo.toml write this:</h3>
[dependencies]
flate2 = "1.0.24"
![image](https://github.com/sanketpalkar9/Rust-project/assets/120122187/523cdb34-a446-4300-a5a8-a4b3e1134eea)




<h1>How to run the program</h1>

cargo run source_file_name compressed_file_name
![image](https://github.com/sanketpalkar9/Rust-project/assets/120122187/4a9ef862-28e8-4256-88d6-77a5e2ad4c27)

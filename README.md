

# Custom Shell in C

A fully functional **custom shell** implemented in C, supporting built-in commands, external commands, piping, I/O redirection, background processes, job control, and signal handling.

---

## Features

- **Built-in commands**: 
  - `cd` – change directory  
  - `pwd` – print current directory  
  - `mkdir` – create directory  
  - `touch` – create file  
  - `exit` – exit shell  

- **External commands**: Run any program available in your system (e.g., `ls`, `cat`, `grep`, etc.) using `fork()` and `execvp()`.  

- **Piping**: Chain multiple commands using `|`.  
- **I/O Redirection**: Supports `<`, `>`, and `>>`.  
- **Quoted Strings & Escape Characters**: Handles single/double quotes in commands.  
- **Background Execution**: Run commands in background using `&`.  
- **Job Control**:
  - `jobs` – list background jobs  
  - `fg <job_id>` – bring a background job to foreground  
- **Signal Handling**:
  - `Ctrl+C` – interrupt foreground process  
  - `Ctrl+Z` – suspend foreground process  

---

## Project Structure


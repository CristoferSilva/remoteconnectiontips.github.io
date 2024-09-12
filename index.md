# Remote connection tips

Criado: September 11, 2024 5:20 PM
Revisado: No

### Tmux

[Tmux para iniciantes](https://dev.to/collabcode/tmux-para-iniciantes-4kg8)

- Commands
    1. Create a session
        
        ```bash
        tmux new -s nameOfSession
        ```
        
    2. List all sessions
        
        ```bash
        tmux ls
        ```
        
    3. Kill a session
        
        ```bash
        tmux kill-session -t nameOfSession
        ```
        
    4. Attach a session
        
        ```bash
        tmux a -t nameOfSession
        ```
        
    5. Leave a session
        
        ```bash
        ctrl+b+d
        ```
        
    6. Run a python experiment in a session
        
        ```bash
        #once you're in the tmux terminal you'll run:
        python3 your_python_script.py
        ```
        

### **Multiprocessing — Process-based parallelism**

[multiprocessing — Process-based parallelism](https://docs.python.org/3/library/multiprocessing.html#multiprocessing.pool.Pool)
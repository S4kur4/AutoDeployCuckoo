# AutoDeployCuckoo
This tool can help you automatically deploy a Cuckoo sandbox it (only) has been tested on Ubuntu Desktop 18.04.5.

See this article for more infomation: [Install a Cuckoo Sandbox in 12 steps](https://0x0c.cc/2020/03/19/Install-a-Cuckoo-Sandbox-in-12-steps/)

## Usage
You need to prepare a clean Ubuntu (Ubuntu Desktop 18.04.5 is recommended) at first, then open terminal to run following command:

```
bash <(curl -sS -L https://raw.githubusercontent.com/S4kur4/AutoDeployCuckoo/master/install.sh)
```

Or you can download `install.sh` and maunually run it.

You may need to enter one or more times root password while it running. If you're not using Ubuntu 18.04.5, I'm not sure if this tool will have problems, as many of the dependencies are strongly associated with the system, in which case you may need to debug by yourself. And If you have any other questions, please submit an issue.

![Cuckoo Sandbox](https://i.loli.net/2020/03/19/EAD2USLqxmwfYnp.png)

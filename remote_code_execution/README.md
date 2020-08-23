# Remote Code Executer

Execute your code on any wireless device immediately.

# Usage

- Run `remote_exec_recv <modemSide>` on any wireless device. It always listens to master after running this. (Unless shutdown, reboot etc. obviously)
- Default parameters: `modemSide: "right"`


- Run `remote_exec_master <codeFileName> <modemSide> <receiverId>` on any wireless device.
- Default parameters: `codeFileName: "remote_exec_code", modemSide: "back"`


# Example

On master: `remote_exec_master turtle_tnt_bomber right 32`

On listeners: `remote_exec_recv left`

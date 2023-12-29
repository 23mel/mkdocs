## Tasks
Try these after going through [ROS tutorials](ros-tutorials.md).

1) Basic Chat Program
- Should have two separate ROS Nodes
- Message typed in one Node should be displayed in the other Node
- Messages should go through ROS
- Messages should be visible via `rostopic echo`
- Be able to record via `rosbag` the messages being sent and received

2) Further Features (Optional)
- Configurable topic names via Parameter server
- Config file as `.yaml` file
- Add a bot node that sends a message every X seconds
- Use a `.launch` file to start multiple nodes at once

Even though implementing parameter and launch file are optional, you should at least have an understanding on how those concepts work.
___
#### Note
If you run into this particular error: /usr/bin/env: ‘python3\r’: No such file or directory  
You can try installing dos2unix, before converting your scripts. You can do with something like this:  
```bash
sudo apt install dos2unix
```

Once installed, you can convert your script accordingly:  
```bash
dos2unix <file_name>.py
```

Separately, do try to run your script locally and see if it's working, you will also need to take note to include the shebang line in your script.  
```python
#!/usr/bin/env python3
```
Note that above is for `python3`, use `python` if necessary.

Reference link: https://askubuntu.com/questions/896860/usr-bin-env-python3-r-no-such-file-or-directory


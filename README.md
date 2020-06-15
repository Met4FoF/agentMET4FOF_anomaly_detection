# _agentMet4FoF_ use case anomaly detection based on machine-learning

This is supported by European Metrology Programme for Innovation and Research (EMPIR)
under the project
[Metrology for the Factory of the Future (Met4FoF)](https://met4fof.eu), project number
17IND12.

## Anomaly detection

With the provided code we showcase an agent-based machine learning approach for
 online anomaly detection of (in our case simulated) sensor readings.
  
## Getting started

In case you are using PyCharm, you will already find proper run configurations at the
appropriate place in the IDE. It expects that you have prepared and defined a default
interpreter.

If you are not using PyCharm, of course you can run the script files as usual.

If you have any questions please get in touch with
[the author](https://github.com/majidam20).

### Dependencies

To install all dependencies in virtual environment based on Python version 3.7 first
install `pip-tools` and afterwards use our prepared `requirements.txt` to get
everything ready.

```shell
$ python3.7 -m venv my_anomaly_detection_use_case_env`
$ source my_anomaly_detection_use_case_env/bin/activate
$ pip install --upgrade pip setuptools pip-tools
$ pip-sync
```

### Scripts

The interesting parts you find in the file

- `agentMET4FOF_anomaly_detection/anomaly_detection.py`

### Note

In the event of agents not terminating cleanly, run

```shell
taskkill /f /im python.exe /t
```

in Windows Command Prompt to terminate all background python processes.

## References

For details about the agents refer to the
[upstream repository _agentMET4FOF_](https://github.com/bangxiangyong/agentMET4FOF)

## Screenshot of web visualization
![Web Screenshot](https://github.com/bangxiangyong/agentMet4FoF/blob/master/screenshot_met4fof.png)
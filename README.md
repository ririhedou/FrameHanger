# FrameHanger
```
  ______                        _    _
 |  ____|                      | |  | |
 | |__ _ __ __ _ _ __ ___   ___| |__| | __ _ _ __   __ _  ___ _ __
 |  __| '__/ _` | '_ ` _ \ / _ \  __  |/ _` | '_ \ / _` |/ _ \ '__|
 | |  | | | (_| | | | | | |  __/ |  | | (_| | | | | (_| |  __/ |
 |_|  |_|  \__,_|_| |_| |_|\___|_|  |_|\__,_|_| |_|\__, |\___|_|
                                                    __/ |
                                                   |___/
```

FrameHanger is a tool to extract static and dynamic injected iframes from webpages

It is able to

- [x] Extract statically injected Iframe
- [x] Gather information on the Iframe and its host HTML content
- [x] Selectively and Dynamically executing JavasScript to detect dynamic Iframe injection
- [x] Detect iframe destinations within JavaScript


# Install dependencies

```
bash install.sh
```

## How to use
```

```


## A Demo

The demo shows that FrameHange could extract injected iframes from obfuscated JavaScript code.
The JavaScript code is located at benchmark/dynamic_obfuscation.html.

python dynamic_detection.py benchmark/dynamic_obfuscation.html .


![](https://github.com/ririhedou/FrameHanger/blob/master/benchmark/demo.gif)

## Disclaim

A research prototype, use at your own risk

If you feel this tool is helpful, citing the paper is highly encouraged.

```
@inproceedings{framehanger,
  title={FrameHanger: Evaluating and Classifying Iframe Injection at Large Scale},
  booktitle={Proc. of 14th EAI International Conference on Security and Privacy in Communication Networks (SecureComm)},
  year={2018}
}
```
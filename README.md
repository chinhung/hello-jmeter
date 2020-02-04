
## About
JMeter is a load testing tool. In this repository, a load testing will be run by JMeter command.

## Setup
1. Install JMeter. In macOS, use Homebrew:
    ```sh
    brew install jmeter
    ```
2. Open JMeter GUI to edit the test plan file(*.jmx):
    ```sh
    jmeter
    ```

## Run Test
```sh
cd path/of/this/repo
chmod +x run.sh // make the script file executable
./run.sh
```


## Future Work
- Dockerize this application.
- Integrate with CI system.
- Survey alternatives because jmx file is too difficult to read by human.


## Reference
- https://blog.yowko.com/mac-jmeter/
- http://dog0416.blogspot.com/2017/06/stress-test-jmeter-command-line-mode.html
- https://dotblogs.com.tw/grayyin/2016/08/15/173243
- https://tpu.thinkpower.com.tw/tpu/articleDetails/923
- https://apple.stackexchange.com/questions/235128/how-do-i-run-a-sh-or-command-file-in-terminal
- https://kknews.cc/zh-tw/code/vy528el.html

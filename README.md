# pswhatsnewpy37
## 4. The Built-in Breakpoint Function
### 1 Introducing the Breakpoint Function
```
imoprt pdb;
pdb.set_trace()
```
### 2 Calling Breakpoint
### 3 Disabling Breakpoint
```
export PYTHONBREAKPOINT=0
```
### 4 Customizing the Debugger
### 5 Remote Debugging with Breakpoint

## 7. performance inprovements
### 2 Will you see an Improvement in Speed?
```
python -m perf timeit -s 's="asdf"*100' -- 's.find("s")'
```
### 5 Faster Method Calling
```
pip install performance
pyperformance run --python=python3.7 -o 7.json
```

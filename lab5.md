# Scenario 3


# 1.Original Post
What environment are you using (computer, operating system, web browser, terminal/editor, and so on)?
I am using MacOs.


Detail the symptom you're seeing. Be specific; include both what you're seeing and what you expected to see instead. Screenshots are great, copy-pasted terminal output is also great. Avoid saying “it doesn't work”.

![image info](lab5.png)


Detail the failure-inducing input and context. That might mean any or all of the command you're running, a test case, command-line arguments, working directory, even the last few commands you ran. Do your best to provide as much context as you can.

bug.sh contains the following code:
```
VAR=7

if [[1 -eq $VAR ]]
then
  echo "it was 1"
fi
```



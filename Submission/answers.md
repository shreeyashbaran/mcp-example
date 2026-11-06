# Assignment Answers

1. The server listed 8 tools in Part 1 and 9 tools in Part 3.
   The client used the same `list_tools()` method to discover `predict_both`. I added the tool on the server and called it by name in the client.

2. The models disagreed on 8 of the 114 test patients.

   | Patient index | Correct model |
   | --- | --- |
   | 3 | Logistic regression |
   | 25 | Logistic regression |
   | 48 | Logistic regression |
   | 53 | KNN |
   | 76 | Logistic regression |
   | 80 | Logistic regression |
   | 99 | Logistic regression |
   | 102 | Logistic regression |

3. Logistic regression was right more often when the models
   disagreed. It was correct on 7 of those 8 patients, while KNN
   was correct on 1.

4. The description tells the AI app what the tool does so it can
   decide when to use it. For example, the description of
   `predict_both` tells the app it can get both predictions and
   check whether they agree in one call.

5. The audit log lets me trace what happened after a tool call.
   I can use the request ID to find a specific call, see which
   tool ran, and check whether it succeeded or failed.

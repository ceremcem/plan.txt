# Plan.txt

Planning application that handles async tasks. 


## Cheatsheet 

| Symbol | Meaning |
| -----  | ------- |
| o      | starting |
| @      | started |
| x      | finished |
| !      | cancelled |
| >      | async task |
| "foo"  | set task name to "foo" |
| *      | sync task (`await`) |
| [foo, bar] |  wait for "foo" and "bar" tasks to finish (use "*" for "all started tasks in this context") |
| +foo       | add "foo" label (add this task to "foo" group) |
| {foo}      | "foo" is a BOM (Bill Of Materials) entry. Dump the BOM via: <br/><br/><code>grep -Po '{.+}' plan.txt</code> |


# Example 


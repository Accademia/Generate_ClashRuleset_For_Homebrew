
功能与目的：
--------------------------------
本项目有两个核心功能：
 - 自动生成本地homebrew list 更新时，所需的 clash 分流规则 （已防止因为GFW而影响升级过程）

<img width="1081" height="1006" alt="longshot20250923095550" src="https://github.com/user-attachments/assets/2b1239ef-9d8b-4db2-bc46-6364451cc040" />

.


使用方法：
--------------------------------

下面两个脚本功能完全相同

usercmd_brewlist_to_ruleset_parallel （推荐）

usercmd_brewlist_to_ruleset_serial

推荐使用第一个脚本，并行处理，比第二个脚本（串行处理）快几十倍。

$ 生成的规则 在 当前目录 ：./clash_rules.yaml


.


声明：
--------------------------------
   
 - 本工程所有源代码，均使用MIT协议分发

 - 本脚本，代码均来自AI，没有任何人工编写的源代码。参与编程的AI包括：
   编程者：OpenAI ChatGPT5 Pro Agent 

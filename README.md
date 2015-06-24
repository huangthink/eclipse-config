Eclipse CodeStyle Config
========

## 设置等宽字体

	Window -> Preferences -> General -> Appearance -> Colors and Fonts -> Basic -> Text Font -> Edit -> DejaVu Sans Mono 

## xml格式化
	Window -> Preferences -> XML －> XML files -> Editor -> Line width: 999
	Window -> Preferences -> XML －> XML files -> Editor -> indent using spaces
	Window -> Preferences -> XML －> XML files -> Editor -> indentation size: 2

## VCS提交设置
	Window -> Preferences -> Team -> Ignored Resources -> Add Pattern -> .settings
	Window -> Preferences -> Team -> Ignored Resources -> Add Pattern -> .classpath
	Window -> Preferences -> Team -> Ignored Resources -> Add Pattern -> .project
	Window -> Preferences -> Team -> Ignored Resources -> Add Pattern -> target 
	Window -> Preferences -> Team -> Ignored Resources -> Ignore Pattern -> 全选(除了core)

## workspace设置
	Window -> Preferences -> General -> Workspace -> Text file encoding: UTF-8
	Window -> Preferences -> General -> Workspace -> New text file line delimiter: Unix

## 开发模板设置(文件在本工程/codestyle/)
	Window -> Preferences -> java -> Code Style -> Use 'is' prefix for getters that return boolean: 不选
	Window -> Preferences -> java -> Code Style -> Clean Up -> Import -> CleanUp.xml  
	Window -> Preferences -> java -> Code Style -> Formatter -> Import -> Formatter.xml    
	Window -> Preferences -> java -> Code Style -> Code Templates -> Import -> CodeTemplates.xml  
 
## java编译器
	Window -> Preferences -> java -> Compiler -> Compiler compliance level: 1.6
 

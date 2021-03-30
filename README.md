<!--
 * @Author: xuwenjie
 * @Date: 2021-01-13 16:46:45
 * @LastEditors: xuwenjie
 * @LastEditTime: 2021-03-30 14:48:10
 * @Description:  
 * @FilePath: /formate-custom/README.md
-->
# Formate-custom: CSS, LESS and SCSS Formatter

>Forked from [formate](https://github.com/mblander/formate), add two configurations.

NOTE: Just use for my custom project.

![Formate: Vertical alignment](images/demo.gif)

## Installation
Install through VS Code extensions. Search for formate.

## Usage
On Windows:
1. CTRL + Shift + P -> Format Document
2. CTRL + ALT + F

On Mac:
1. CMD + Shift + P -> Format Document
2. CMD + ALT + F

## Extension Settings
| Setting                           | Description                                         | Type    | Default  |
|:--------------------------------- |:----------------------------------------------------|:-------:|:--------:|
| formateCustom.enable                    | Enables/disables the extension                      | boolean | true     |
| formateCustom.verticalAlignProperties   | Controls if properties should be aligned vertically | boolean | true     |
| formateCustom.additionalSpaces          | If vertical alignment is on, this setting is to add extra spaces | boolean | 0     |
| formateCustom.includeRootFolders                | Specify which folders need formate. | array | []    |
| formateCustom.withGroup                | Group with line-warp. | boolean | false    |



## Release Notes

| Version | Notes |
|:--------|:------|
| 1.0.5   | 完善去掉逗号折行逻辑
| 1.0.4   | 去掉逗号折行逻辑
| 1.0.3   | update README.
| 1.0.2   | update configuration field.
| 1.0.1   | init



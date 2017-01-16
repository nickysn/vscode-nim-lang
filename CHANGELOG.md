# ChangeLog

## 0.5.13 (18 Dec 2016)
* Added "Nim: Run file" command that run selected file with `F6` keyboard shortcut
* Fixed "Provide more details in symbols window" [#27](https://github.com/pragmagic/vscode-nim/issues/27)

## 0.5.12 (04 Nov 2016)

* Added support of bundled nimsuggest with compiler that will be available in upcoming Nim 0.15.3 release

## 0.5.11 (23 Oct 2016)

* Fixed nim check multiline result parsing

## 0.5.9 (21 Sep 2016)

* Fixed nim check often hangs and doesn't get killed [#23](https://github.com/pragmagic/vscode-nim/issues/23)
* Fixed signature suggestion wrong behavior [#21](https://github.com/pragmagic/vscode-nim/issues/21)

## 0.5.7 (1 Aug 2016)
* Minor fixes for the signature provider [PR #22](https://github.com/pragmagic/vscode-nim/pull/22)
* Temporary disabled reindex on file change due leak of nimsuggest

## 0.5.5 (1 Aug 2016)
* Added support for parameter hints [PR #19](https://github.com/pragmagic/vscode-nim/pull/19)

## 0.5.4
* Added snippets [PR #18](https://github.com/pragmagic/vscode-nim/pull/18)
* Added a new nimsuggest
* Updated buildOnSave relative to tasks.json
* Fixed [Multiline comments syntax highlight.](https://github.com/pragmagic/vscode-nim/issues/11)
* Minor improvements and stability fixes 

## 0.5.2
* Added multiple projects support
* Fixed some hangs during indexing 

## 0.5.1
* Fixed #12 - Cannot compile nimsuggest 

## 0.5
* Refactored nimsuggest interaction to use EPC mode, removed nimble requirements
* Added info with qualified name for hovered element
* Improved suggest information

## 0.4.10
* Added test project support
* Improved nim check error parsing for macros and templates

## 0.4.9
* Improved database indexes
* Fixed multiline error in nim check
* Fixed nimsuggest problem with mixed case path in windows

## 0.4.6
* Fixed #9 - nimsuggest "attacks" (one process per nim file in workspace)
* Added type index persistence with NeDB

## 0.4.4
* Fixed #7 - Block comments / inline comments are not supported
* Fixed #8 - Terrible experience with clean install w/o nimsuggest

## 0.4.3
* Added workspace symbol search support 
* Rewrote nimsuggest handling to use TCP mode
* Added `nim.licenseString` for inserting default header in new nim files
* Updated `run project` command to run single file in non project mode 
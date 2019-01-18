
# How to properly report an issue

The purpose of this guide is to explain how to report a bug, suggest a feature or improvement, or ask a question in a clear and structured way.

## Introduction

When a new issue is created, you will receive a template to adhere to. A report that does not match the default format may be deleted. 

___

Let's start with the basics. There is a ">" in each section. Please formulate your information behind each one. 

For example:

```
What version of LulzHack are you using?

> [INSERT YOUR INFORMATION HERE]
```
___

## 1.  Report Types

We use different types of reports to clearly structure the Issue Tracker and split the tasks. Depending on the type, the information we need for processing also differs.
If you are not sure what type your report is, read [this article](https://github.com/LulzHack/LulzHack-IssueTracker/blob/master/REPORT_TYPES.md) 

```
What type of report is this?
False Positive, Bypass, Console Error, Crash, Activation Error, Suggestion, Question, Other

> [YOUR INFORMATION]
```
___

## 2. Videos / Pictures

So that we can better understand the error, it is very helpful if a video or in exceptional cases a picture can be provided.
If it is a direct error in the console or when enabling the plugin, it is <em>not necessary</em> to provide a video/image.

The video must be uploaded to a popular video service such as [YouTube](https://youtube.com). 

In addition, the situation in the video should be briefly explained in one or two sentences.

```
If it is a false flag or bypass, please add a video, gif or a unique image. Videos are preferred
because they show the situations better than a combination of images.

Add your video link:
> [LINK TO THE VIDEO/PICTURE]
```

___

## 3. Logs and LUAC Dump/Log

To get enough information, please upload your server log, a LUAC dump and your current LUAC log files.

<strong> - Logs: </strong> Go to your server logs order ("/../logs") and search the file "latest.log" with the current date. Open the document with any text editor, copy the whole content (or only the part with the stacktrace if your message type is "CONSOLE ERROR") and paste it to log.lulzhack.xyz. Copy the link of the document into the "Server Log" field.

<strong> - LUAC Dump: </strong> Enter the command /lulzhack dump in the console or on the server and wait a few seconds. Go to the folder ("/../plugins/LulzHack/dump") on your server. Open the document named dump-"current date + time" with any text editor. Copy all the content and paste it to log.lulzhack.xyz. Copy the link of the document into the "LulzHack Dump" field.

<strong> - LUAC Log: </strong> Go to your server logs order ("/plugins/LulzHack/logs") and search the file "latest.log" with the current date. Open the document with any text editor, copy the whole content and paste it to log.lulzhack.xyz. Copy the link of the document into the "LulzHack Log" field.

```
ServerLogs, LulzHack Log and LulzHack Dump

Add your server log link, uploaded to log.lulzhack.xyz
> [Server Log]

Add your lulzhack log link, uploaded to log.lulzhack.xyz
> [Lulzhack Log]

Add your lulzhack dump link, uploaded to log.lulzhack.xyz
> [LulzHack Dump]

```
___

## 4. Detection report

More detailed information can be added here if it is a <strong>BYPASS</strong> or a <strong>FALSE FLAG</strong>. We need such information in order to be able to reproduce the situation if necessary and thus to be able to examine the problem more exactly. 

This information includes (in the case of a false flag) the client version used, including any installed modifications such as Forge.

```
- What Client Version do u use?
> [ADD CLIENT VERSION]

- List all your installed modifications. If there is none write "/".
> [ADD MODIFICATIONS]

- Which client are you using and which settings have you set (only for BYPASS reports) - NO DOWNLOAD
> [ADD CLIENT + SETTINGS]
```
___

## 5. Further information

If you have further information regarding your report, you can add it in detail in this section. This may include reasons for a false flag or bypass and other known information that may help us fix the problem.

```
Furher information, about the client or any other report related informations.

- Do you have any further information? Let us know!
> [ADD INFORMATION]

```
___




  











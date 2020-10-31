# rMapy

> This is a fork of tkukurin's rmapy repo fork, which is itself a fork of the original.
> 
> This fork includes the following modifications:
> * **Fileless support**: Manage file upload and config without writing to disk (i.e using only `io.BytesIO`). This means rmapy can now run in an unprivileged environment like AWS Lambda.
> * **Some bug fixes,** including better auth/token renewal and function-name bugs
> I'd recommend you use this repo instead of the original, since it is fully backwards-compatible. But you do you!! I use this for [ReMailable](https://github.com/j6k4m8/remailable), so I tend to keep it updated.


This is an (unofficial) Remarkable Cloud API Client written in Python.


### API Support

* ☑️ List content in the cloud
* ☑️ Work with documents & folders
* ☑️ create a folder
* ☑️ move / rename a document or folder
* ☑️ create a document
* ☑️ edit a document
* ☑️ delete a document or folder
* ❎ cli interface
* ❎ export pdf with annotations



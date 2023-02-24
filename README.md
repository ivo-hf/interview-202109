interview-dl

见项目中的笔记本文件。

数据保存在 Azure Blob Storage，共享访问签名(SAS) URI为：

```
SharedAccessSignature=sv=2021-10-04&ss=b&srt=sco&st=2023-02-24T08%3A56%3A20Z&se=2025-03-31T08%3A56%3A00Z&sp=rl&sig=9batnsgfZgfNbAyZT3oH5WsFomZiVmID31gkzu0zqas%3D;BlobEndpoint=https://ivohub.blob.core.chinacloudapi.cn/;
```

可以用 [Azure Storage Explorer](https://azure.microsoft.com/en-us/features/storage-explorer/) (使用连接字符串添加) 或各种语言的 sdk 查看和下载。

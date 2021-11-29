interview-dl

见项目中的笔记本文件。

数据保存在 Azure Blob Storage，共享访问签名(SAS) URI为：

```
    https://ivohub.blob.core.chinacloudapi.cn/interview-dl-data?sv=2019-10-10&st=2021-11-29T05%3A24%3A15Z&se=2024-11-30T05%3A24%3A00Z&sr=c&sp=rl&sig=Q3hN%2BSVRrX9GjAhtR9XB3ZTx%2Fq2HkUwLUUzL4u3jemE%3D
```

可以用 [Azure Storage Explorer](https://azure.microsoft.com/en-us/features/storage-explorer/) (使用共享访问签名(SAS) URI添加) 或各种语言的 sdk 查看和下载。

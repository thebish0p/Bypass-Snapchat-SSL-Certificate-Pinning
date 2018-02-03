# Bypass-Snapchat-SSL-Certificate-Pinning
Bypass Snapchat certificate Pinning using Frida. Should work on any version of Snapchat.

###### Tested on version: 10.24.5.0

###### Usage:
./frida_spawn.py [plain text certificate in PEM format]

###### Running example:
python ./frida_spawn.py -----BEGIN CERTIFICATE-----\nMIIDYDCCAkigAwKBAKIJAP9KPLQlVm59MA0GCSqGSIb3DQDBCwUAMEUxCzAJBgNV\nBAYTAkFVMRMwEQYDVQQIDApTb21lLVN0YXRlMSEwHwYDVQQKDBhJbnRlcm5ldCBX\naWRnaXRzIFB0eSBMdGQwHhcNMTgwMTI5MTgyMjI4WhcNMjAwMTI5MTgyMjI4WjBF\nMQswCQYDVQQGEwJBVTETMBEGA1UECAwKU29tZS1TdGF0ZTEhMB8GA1UECgwYSW50\nZXJuZXQgV2lkZ2l0cyBQdHkgTHRkMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIB\nCgKCAQEA33/lkvuWVuU28FOzHy5/ztu5IMoLT0dT0Kxndxh6B0zZ/UlZm47LtmAl\nehIP7yO6l6AwJnJeLUIRqPBnJ5WHcAFsGVOQyAXMndp5ejT7UD43lejpciTQTHO2\nNK+nCHAkoHcDTFubEaM8zaEvedgAlnh0MaTdYGFCQefPvYc605vr32hT9Z7wstvK\nMGRR0J2OFRSAWXNrE5VLEtC+yGgfpOzDL/mPPMyLUOYMNNPcn0CIxpVFxD/6to2A\nnuO6z6onTEGge/VDJq5EuaCbFzxmVtsVfKVpmQIMsya3gwMBoCw+IAgY2nQHxCbE\nbzEQgmquKO/y4xilYFRw9fJQ+a0LuQIDAQABo1MwUTAdBgNVHQ4EFgQU9TQKcLB+\nETWvNXZQ5JZapWe3ZBMwHwYDVR0jBBgwFoAU9TQKcLB+ETWvNXZQ5JZapWe3ZBMw\nDwYDVR0TAQH/BAUwAwEB/zANBgkqhkiG9w0BAQsFAAOCAQEAWMtNTydexDIqB/qG\nGLaq1hVo22fn5T1LpISD8kG1og/7OcE++RATjT/ip/JhiStGOwUqepuNqPJGWa92\n0DTUEVSVqeQxxEd1sou42czt37JbE9nnXQ9JL1PQS4hAva+vfiB4aHosBC7frVVK\n+qpVeGkdSFhJpXeHP5bvbI7w1c57Y6ky8+LFEafoFIV0yeDBC90tROwMXEXszrp8\nTenUqNfLPdKK7LnWLjV7BxfTK07iaEx2QLmwMU6PQSFj2YjiLptvrZrrXlpCMeb5\n1E1l3SDbw3ydb20JAbTVpcJziGl0aGaPj/vuihuSikT2FqWWXSbKLEEBKgUaS1yy\n7bziVQ==\n-----END CERTIFICATE-----\n

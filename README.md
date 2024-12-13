# secret-key-env-test-lambda

The base code template was created using `sam init` and selecting basic hello world lambda template. 

```bash
sam build
sam deploy --guided --parameter-overrides NRAccountId=<NRAccountId> NRLiceseKey=<NRIngestKey>
```

Delete resources after testing

```bash
sam delete
```
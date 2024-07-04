# Solution

1. Updated terraform code to create the lambda function and create function url and display the URL as terraform output.
2. To run

    ```bash
        $ cd terraform
        $ terraform init
        $ terraform apply --auto-approve
    ```

3. Function URL: `https://n4cfr5pkuifokrz4q6km4dmqim0pigpw.lambda-url.us-west-1.on.aws/`

4. To test

    ```bash
        $ curl -X GET https://n4cfr5pkuifokrz4q6km4dmqim0pigpw.lambda-url.us-west-1.on.aws/
        {"price":1429}
    ```
# Price forecasting for AWS spot price using LSTM

## Comando para baixar arquivo

aws ec2 describe-spot-price-history --instance-types m1.large --product-description "SUSE Linux" --availability-zone "us-west-1a" --start-time 2022-10-28T00:00:00 --end-time 2023-04-02T00:00:00 > spot-price-history.json
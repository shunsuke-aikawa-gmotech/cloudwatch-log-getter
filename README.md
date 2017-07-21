# Cloudwatch Log getter

## Installation

```

pip install boto3

```

## Parameters

* log streat name (string)--<br>[REQUIRED]
* start date (string)--<br>[REQUIRED]<br>[%Y/%m%dT%H:%M]
* end date (string)--<br>[%Y/%m%dT%H:%M]


```

python getter.py [log stream name] [start date] [end date]

cat ./log/{log streat name}_{start date}.log

```
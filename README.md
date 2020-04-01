# launch-time-qa

Empty Project with (Instruments: Launch Time) traces to show how bad many dependencies influence your Launch time

# QA 

To get metrics from the launch time, please read the blog post at: https://medium.com/@morgancollino/testing-your-app-launch-time-ios-e3d1471dda54?sk=0ef1da134a9de5628741d9701816d533

# Results

## Traces: Initializing - System Interface Initialization:

Test device: 
iPhone 11, os version: 13.3.1.

### 0 Dynamic dependencies:

Cold Launch: 314ms

Warm Launch: 172ms

### 6 Dynamic dependencies:

Cold Launch: 421.13ms

Warm Launch: 156ms

### 15 Dynamic dependencies:

Cold Launch: 797ms/564ms

Warm Launch: 222ms/174ms

### 32 Dynamic dependencies:

Cold Launch: 912.29ms

Warm Launch: 208/209ms

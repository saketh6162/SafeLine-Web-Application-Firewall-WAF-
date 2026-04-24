# 🚦 Rate Limiting Analysis

## Configuration

* Requests: 20 per 10 seconds
* Action: Block
* Duration: 60 minutes

## Testing Method

* Rapid browser refresh
* Multiple requests using curl

## Result

* Requests exceeded threshold
* WAF temporarily blocked access

## Conclusion

Rate limiting prevents abuse by restricting excessive requests from a single IP address, helping mitigate DoS attacks.

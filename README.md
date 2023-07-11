# Outcome Auditing Proxy

The `outcome-auditing` service is responsible for auditing _outcomes_ (feedback) from users of insights and payment allocation services. These outcomes will then, eventually, be used to fine-tune `cip` opinions about attributes. This will be helpful in reducing fraud, enabling more efficient allocation of un-identified payments to `HMRC`. 

This proxy allows consuming services in MDTP and the HMRC coroporate tier to call the underlying `outcome-auditing` service in the private zone.

## Contact

Our preferred contact method is our public channel in HMRC Digital Slack: `#team-cip-attribute-reputation`

If you do not have access to Slack, please email us at `cip-attribute-reputation-g@digital.hmrc.gov.uk`

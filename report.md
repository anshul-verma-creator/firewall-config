# Firewall Configuration Report

## Objective

To configure and test a firewall rule that blocks inbound traffic.

## Tool Used

Windows Defender Firewall with Advanced Security

## Firewall Rule

- Direction: Inbound
- Protocol: TCP
- Port: 23
- Action: Block

## Steps Performed

1. Opened Windows Defender Firewall.
2. Created a new inbound rule.
3. Blocked TCP Port 23.
4. Verified the rule.
5. Deleted the rule after testing.

## Outcome

The firewall successfully applied the rule and prevented inbound connections on the specified port.

## Conclusion

Firewalls are an important security control that filter network traffic according to administrator-defined rules. Blocking unused ports helps reduce the attack surface of a system.
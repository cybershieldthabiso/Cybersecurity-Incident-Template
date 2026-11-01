# Phishing Incident Response Checklist

### Phase 1: Identification & Triage
- [ ] Extract full email headers (Received, Return-Path, Authentication-Results).
- [ ] Inspect links and domains using URL analysis tools.
- [ ] Submit file attachments to sandbox for analysis.

### Phase 2: Containment & Eradication
- [ ] Block malicious sender domain on Email Gateway.
- [ ] Remove malicious email from all targeted user inboxes.
- [ ] Revoke active sessions for compromised users.

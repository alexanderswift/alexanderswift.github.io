---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #ffffffff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---
# Motorcycle Co, Data Breach
<style>
.vspace { height: 3.5rem; }
</style>
Incident review & plan addressing issues.
<style>
.vspace { height: 3.5rem; }
</style>
<div class="vspace" aria-hidden="true"></div>

##### Alexander Swift

<!-- CSS class variant -->
<style>
.headshot-wrapper {
  text-align: center;
  margin: 0.5rem 0;
}
.headshot {
  width: 68px;
  height: 68px;
  border-radius: 50%;
  object-fit: cover;
  display: inline-block;
  vertical-align: middle;
}
</style>
<div class="headshot-wrapper">
  <img src="./me.jpeg" alt="Alexander Swift — headshot" class="headshot" />
</div>

---
### The Incident & Business Impact
**2,000 customer Personally Identifiable Information (PII) records potentially compromised**
- Names, emails, phones, purchase inquiries exposed
- Attack path: Employee endpoint → Database → SQL injection
- Detection time: Last 7 days (performance degradation, not security alerts)
- 
- **Root cause: We cannot confirm full scope—insufficient logging**

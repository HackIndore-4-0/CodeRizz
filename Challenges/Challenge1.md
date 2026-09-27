Challenge 1: Automated Cross-Source Verification Pipeline Implement a verification 
microservice that combines social media data with official news feeds for event 
detection. The engine must automatically cross-reference anomalous spikes in social 
media disaster mentions with authoritative data streams (such as official RSS feeds or 
meteorological APIs) within a sliding time window, requiring strict corroboration before 
escalating an "unverified" event to an "actionable" status. 
Expected Outcome: 
● A working backend pipeline that ingests mock social media data alongside 
simulated official news feeds. 
● A scoring logic that prevents isolated, false-positive social media panic from 
triggering a full system alert. 
● Dashboard visualization demonstrating the state transition of an event from 
"unverified" to "actionable" based on cross-source validation to ensure a reliable 
response.
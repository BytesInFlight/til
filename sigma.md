# Useful Sigma Commands

* List all the available backend and pipeline plugins `sigma plugin list`
* List the available query language target platforms `sigma list targets`
* List the available processing pipelines `sigma list pipelines`

# Typical Setup Sequence

1. Install the Splunk plugin to make Splunk an available target platform `sigma plugin install splunk`
2. Confirm the installation succeeded `sigma list pipelines`
3. Install the Windows pipeline `sigma plugin install windows`
4. Install the Sysmon pipeline `sigma plugin install sysmon`

# Output to a Target Query Language Examples
* `sigma convert -t splunk -p sysmon .\image_load_susp_dll_load_system_process.yml`
* `sigma convert -t splunk -p splunk_windows .\win_security_dcsync.yml`
* `sigma convert -t splunk -p splunk_windows .\win_security_susp_lsass_dump.yml`
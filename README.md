# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

Threat actors are targeting internet-accessible refrigeration management interfaces and industrial temperature controllers, exploiting vulnerabilities, authentication weaknesses and insecure configurations to gain unauthorized access.

The affected technologies include:

- Danfoss AK-SM and AK-SC refrigeration controllers.
- Copeland XWEB refrigeration management systems.
- Dixell XWEB remote monitoring systems.
- Other remotely accessible industrial refrigeration and temperature-control equipment.

Following successful access, attackers can manipulate refrigeration configurations, including temperature setpoints, defrost schedules and operating parameters.

These changes can force refrigeration equipment into continuous heating or defrost cycles, resulting in elevated temperatures, spoiled food and other temperature-sensitive products, equipment damage, operational disruption and potential fire hazards. 

 The **Outbreak Response - Refrigeration Control Systems Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.3.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/refrigeration-control-systems-attack) contains information about the outbreak alert **Outbreak Response - Refrigeration Control Systems Attack**. 

## Background: 

The attacks began in France on October 11–12, 2026, when threat actors compromised refrigeration controllers at approximately 700 retail locations. Attackers manipulated equipment configurations, including defrost parameters, causing refrigeration units to operate at elevated temperatures. The incidents resulted in significant inventory losses and at least 15 reported fires.

A subsequent wave of incidents on November 1–2 affected refrigeration systems across multiple European countries, including Belgium, Estonia, Finland, Ireland, Luxembourg, the Netherlands and Sweden. 

## Announced: 

Organizations operating industrial refrigeration and cold-chain infrastructure should immediately review their exposure, secure remote access and investigate unexpected changes to refrigeration configurations. 

## Latest Developments: 

November 13, 2026: Ireland's National Cyber Security Centre disclosed six previously unknown pre-authentication remote code execution vulnerabilities affecting Danfoss AK-SM800A controllers. The vulnerabilities have not yet received CVE identifiers, and no confirmed security fixes were available at the time of disclosure.
https://ncsc.gov.ie/pdfs/2611130306_New_Vulnerabilities_in_Refrigeration_Controllers.pdf

November 9, 2026: FortiGuard Lab release a Threat Signal report.
https://www.fortiguard.com/threat-signal-report/6553/ot-refrigeration-control-systems-attack

November 9, 2026: French authorities attributed the October attacks to the Nation State Actors.
https://www.cert.cyber.gouv.fr/uploads/CERTFR-2026-CTI-009.pdf

November 5, 2026: CISA, the FBI, HHS, USDA and the U.S. Department of Transportation issued a joint warning about malicious cyber activity targeting industrial refrigeration and cold-chain monitoring systems globally.
https://www.ic3.gov/CSA/2026/261105.pdf?trk=article-ssr-frontend-pulse_little-text-block 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|

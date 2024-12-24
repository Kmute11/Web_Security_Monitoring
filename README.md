# Web_Security_Monitoring
PAYMENT GATEWAY ATTACK: SPLUNK MONITORING

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Security Monitoring - Payment Gateway Attack</title>
</head>
<body>
    <header>
        <h1>Web Security Monitoring: Payment Gateway Attack</h1>
    </header>

    <section>
        <h2>Overview</h2>
        <p>
            Configured and implemented Elastic SIEM and Splunk to monitor security events and detect potential threats. 
            Performed log analysis to identify vulnerabilities, including payment gateway traversal and UI functionality issues, using both platforms. 
            Conducted real-time threat detection and response by setting up alerts for brute-force login attempts, unauthorized payment activities, and data breaches. 
            Collaborated with the development team to address identified vulnerabilities, improving the overall security posture.
        </p>
    </section>

    <section>
        <h2>Key Vulnerabilities</h2>

        <article>
            <h3>CVE-2021-45046</h3>
            <p>
                <strong>Description:</strong><br>
                This vulnerability in the Apache Log4j2 library allows an attacker to craft malicious input data that causes information leaks and, in some cases, remote code execution (RCE) under specific configurations.
            </p>
            <p>
                <strong>CVSS Score:</strong><br>
                <ul>
                    <li>Attack Vector (AV): Network (N)</li>
                    <li>Attack Complexity (AC): Low (L)</li>
                    <li>Privileges Required (PR): None (N)</li>
                    <li>User Interaction (UI): None (N)</li>
                    <li>Scope (S): Changed (C)</li>
                    <li>Confidentiality Impact (C): High (H)</li>
                    <li>Integrity Impact (I): High (H)</li>
                    <li>Availability Impact (A): High (H)</li>
                </ul>
                <strong>Base Score:</strong> 9.0 (Critical)
            </p>
        </article>

        <article>
            <h3>CVE-2019-12384</h3>
            <p>
                <strong>Description:</strong><br>
                A vulnerability in Jackson, a popular JSON library, allows deserialization of malicious objects, leading to remote code execution (RCE).
            </p>
            <p>
                <strong>CVSS Score:</strong><br>
                <ul>
                    <li>Attack Vector (AV): Network (N)</li>
                    <li>Attack Complexity (AC): Low (L)</li>
                    <li>Privileges Required (PR): None (N)</li>
                    <li>User Interaction (UI): None (N)</li>
                    <li>Scope (S): Unchanged (U)</li>
                    <li>Confidentiality Impact (C): High (H)</li>
                    <li>Integrity Impact (I): High (H)</li>
                    <li>Availability Impact (A): High (H)</li>
                </ul>
                <strong>Base Score:</strong> 9.8 (Critical)
            </p>
        </article>
    </section>
</body>
</html>

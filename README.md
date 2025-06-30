# CS-305-Artemis-Finacial-Project
Artemis Financial was the client for a secure software refactoring project I worked on. As a financial services company, they handled sensitive customer data and needed to modernize their application’s security to reduce risk and meet industry standards. Their Java-based software had several vulnerabilities, including outdated encryption practices, lack of HTTPS, and missing data integrity checks.

My role was to assess the software for vulnerabilities and implement updated security measures. One of the things I did well was identifying critical weaknesses early on—such as the lack of secure communication protocols, no use of checksums for file validation, and missing hashing for stored or transmitted data. I focused on applying layered security strategies. For example, I generated secure certificates using keytool, configured HTTPS correctly, implemented SHA-based hash functions to verify data integrity, and enforced stricter input validation to protect against injection attacks.

Writing secure code is vital in the financial sector. Beyond just preventing technical failures, it helps safeguard user trust, ensure regulatory compliance, and protect the company’s overall stability. Security adds long-term value to any product by reducing both reputational and legal risks.

One of the more challenging aspects of the vulnerability assessment was understanding how each fix would impact the existing system. Since I was working with legacy code, even small changes had the potential to cause unexpected behavior. I used a mix of static code analysis and targeted testing to confirm that security improvements didn’t introduce new bugs or break functionality.

To strengthen the system’s defenses, I implemented certificate-based encryption for data-in-transit, added hash-based integrity checks, and refactored input validation logic. Looking ahead, I would like to use tools like OWASP ZAP, SonarQube, or Snyk to streamline vulnerability detection and mitigation prioritization.

To ensure the software was both functional and secure, I followed a structured testing process: first validating functionality with unit and functional tests, then running security checks against updated components. After each refactor, I reviewed the code for new vulnerabilities and documented my decisions to support maintainability and transparency.

If I were to present this project to a future employer, I’d highlight the before-and-after code comparisons, my implementation of certificate-based security, and the documentation I created to support secure development practices. It’s a strong example of applying modern security principles in a real-world, client-facing context.

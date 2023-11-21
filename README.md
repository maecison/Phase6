# Phase 6
Security Recommendations

What is your security recommendation? Why did you choose it?
-	My security recommendation would be for mobile app authentication architecture, specifically to implement strong password policies. We chose this recommendation because we require users to create accounts that include a username and password. It is important for our users to be safe from unauthorized access. For a minigame app, this recommendation makes sense compared to others that are overkill and unnecessary. One would be two-factor authentication because since we do not ask the users for any personal information, users would find it a cumbersome process.

Who does the recommendation benefit (end-user, developer, etc.)?
-	The recommendation benefits both end-users and developers. This benefits end-users because they feel secured and safe when using the app. It is less likely for their account to be hacked or compromised due to this recommendation. End-users are more likely to keep using the app knowing we are taking safety measures. This benefits developers because the app they made is less likely to have a security breach. If a security breach occurs, the reputation of the developers could be affected. Developers will feel more relaxed and not prone to any legal liabilities.

If the recommendation was found somewhere other than the provided checklist, include a link to it.
-	This was found in the provided checklist: https://github.com/muellerberndt/android_app_security_checklist

When would the recommendation have to be implemented (based on how serious the security risk is)?
-	This security recommendation should be implemented as soon as possible since the security risk is very high. It should be prioritized, especially before it is released to the public. This will ensure that the users are protected from the very beginning.

Why do you think your project needs your recommendation?
-	User authentication and password security should be implemented in every project if they require login information or any type of personal information. Users tend of reuse passwords which could lead to breaches if password policies are not strict. It does not only protect user accounts, but it also protects the integrity of the app itself. We need users to trust the app in order to build a community of loyal players.

How do you think your recommendation could be applied?
-	Implementing strong password policies would involve setting up criteria for password creation during the “Create Account” setup process. These criteria could include a minimum length, requiring a mix of uppercase and lowercase letters, numbers, and special characters, and not allowing commonly used or easily guessable passwords. As for user interface, we would give the user real-time feedback on their password's strength as they type it. This could be done through a password strength meter and messages that tell the user what criteria their password is not yet meeting. For its development, we would need to find a framework to implement to check the password’s complexity.

How feasible would the implementation be?
-	The implementation would very much be feasible. Most modern mobile app development frameworks and libraries include easy ways to enforce password policies. It would require some additional coding and testing, but the overall impact on development time and resources should be minimal. If it does require lots of time to implement this recommendation, it is still something we need to prioritize as it is a worthwhile investment.
-	There are users that might prefer more simpler passwords, however with the use of proper UI design and user education, we can guide the users to complying with our strong password policy.

# ValidateStrongPasswordFunction
Write an authentication function in python to authenticate the user's password

Goal:
1. Perform input validation. Check for:

    The type of data allowed (e.g., decimal number, currency)
    The range of data allowed
    The type of encoding allowed
    Which characters are allowed
    The minimum and the maximum length of data


Notes from Rangeforce (make sure to credit):
For web applications, validate all inputs coming from untrusted sources (user, input files, remote databases, parameters, URLs, HTTP header content, data redirects, and active page content such as Flash, AJAX, and so forth) before processing, and ensure they:

    Are in a specific character set (e.g., UTF-8)
    Contain the expected data types
    Contain the expected data range
    Contain the expected data length
    Contain allowed characters
    Do not contain disallowed characters, such as null bytes (%00), line control characters (%0d, %0a, \r, \n), and path modification characters (../ and ..).

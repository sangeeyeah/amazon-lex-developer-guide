# Built\-in Slot Types<a name="howitworks-builtins-slots"></a>

Amazon Lex supports built\-in slot types from the *Alexa Skills Kit*\. You can create slots of these types in your intents\. This eliminates the need to create enumeration values for commonly used slot data such as date, time, and location\. Built\-in slot types do not have versions\. 

For a list of available built\-in slot types, see [Slot Type Reference](https://developer.amazon.com/public/solutions/alexa/alexa-skills-kit/docs/built-in-intent-ref/slot-type-reference) in the Alexa Skills Kit documentation\.

**Note**  
Amazon Lex doesn't support the `AMAZON.LITERAL` built\-in slot type\. 

 Amazon Lex supports the following built\-in slot types\. Slot types marked "Developer Preview" are in preview and might change\. 


| Slot Type | Short Description | Supported Languages | Availability | 
| --- | --- | --- | --- | 
| [AMAZON\.EmailAddress](built-in-slot-email.md) | Converts words that represent an email address into a standard email address | English \(US\) | Developer Preview | 
| [AMAZON\.Percentage](built-in-slot-percent.md) | Converts words that represent a percentage to a number and a percent sign \(%\) | English \(US\) | Developer Preview | 
| [AMAZON\.PhoneNumber](built-in-slot-phone.md) | Converts words that represent a phone number into a numeric string | English \(US\) | Developer Preview | 
| [AMAZON\.SpeedUnit](built-in-slot-speed.md) | Converts words that represent a speed unit into a standard abbreviation | English \(US\) | Developer Preview | 
| [AMAZON\.WeightUnit](built-in-slot-weight.md) | Converts words that represent a weight unit into a standard abbreviation  | English \(US\) | Developer Preview | 

When used with Amazon Lex, the following slot types extend the Alexa Skill Kit slot type\. 


| Slot Type | Short Description | Supported Languages | Availability | 
| --- | --- | --- | --- | 
| [AMAZON\.NUMBER](built-in-slot-number.md) | Converts numeric words into digits | English \(US\) | Developer Preview | 
| [AMAZON\.TIME](built-in-slot-time.md) | Converts words that indicate times into a time format | English \(US\) | Available | 

The built\-in slot types are described in detail in the following sections\.
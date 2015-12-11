# SimpleConvertLibrary

/**
 * Convert any strings into md5
 * @param value takes in any string value
 * @return returns a md5 string
 */

+(NSString *)convertToMd5 :(NSString *)value;

/**
 * Convert any strings into sha1
 * @param value takes in any string value
 * @return returns a sha1 string
 */
+(NSString *)convertToSha1 :(NSString *)value;

/**
 * Convert any strings into sha256
 * @param value takes in any string value
 * @return returns a sha256 string
 */
+(NSString *)convertToSha256 :(NSString *)value;

/**
 * Convert hex value to int
 * @param hexValue takes in any hex value
 * @return returns an int
 */
+(int)convertHextToInt :(NSString *)hexValue;

/**
 * Convert hex value to string
 * @param hexValue takes in any hex value
 * @return returns a string
 */
+(NSString *)convertHexToString :(NSString *)hexValue;

/**
 * Convert an input value to binary with out leading zero
 * @param inputValue takes in any NSUInteger
 * @return returns a binary value without leading zeros
 */
+(NSString *)convertToBinaryWithLeadingZero :(NSUInteger)input;

/**
 * Convert an input value to binary with leading zero
 * @param inputValue takes in any NSUInteger
 * @param length the length of the string value
 * @return returns a binary value with leading zeros
 */
+(NSString *)convertToBinary :(NSUInteger)input strLength :(int)length;

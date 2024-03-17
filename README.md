# ft_strlcpy

The `ft_strlcpy` function provides a safe way to copy strings, ensuring that the destination string is null-terminated even when truncation occurs due to the destination size limit. This implementation offers a reliable alternative to standard string copy functions, which may leave destination strings without null termination.

## Description

`ft_strlcpy` aims to copy the `src` string to the `dest` string, including a null terminator, safely within the bounds of the destination size specified by `size`. It copies up to `size - 1` characters, ensuring that at least one byte is left for the null terminator. This function returns the total length of `src`, providing an easy way to detect truncation.

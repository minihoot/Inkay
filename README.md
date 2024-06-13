# Inkay 

Inkay is an Aroma/WUPS plugin that patches various Nintendo Network URLs on a Wii U to use Pretendo Network instead. It also (for the time being) bypasses SSL verification in most cases. This fork has been slightly modified to connect to a private Miiverse clone.

## Dependencies
Inkay is only supported on the release version of Aroma configured for autoboot/coldboot. For Tiramisu, see [Nimble](https://github.com/PretendoNetwork/Nimble).

## Safety
Inkay's patches are all temporary, and only applied in-memory without modifying your console. The SSL patch, while also temporary, could reduce the overall security of your console while active - this is because it no longer checks if a server is verified. However, this does not apply to the Internet Browser, where SSL still works as expected.

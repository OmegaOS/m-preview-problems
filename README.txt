# List of m-preview-problems (5.1.51)

List of AOSP M-preview problems which should be solved
G2-Common:SEPOLICY related to the removal of init_shell and some other things.
G2-Common:AOSP doesn't include the Camera Headers so it will result into an error related to LGE_CAMERA

Allow a device to generically define its own headers and many other related things in the core/binary.mk file.

G2-Common:Update the GPS related files in the G2-Common devicetree so it can be compiled.
FIX Kernel building as the flags and configurations are in the Boardconfig but they aren't getting executed, so solutions: Make prebuilt or fix kernel building process from the DT
QCOM SEPOLICY: SEPOLICY is outdated for m-preview AOSP need some changes

Project Beer Bottle is a hard drive encryption scheme designed to allow flexible use of a computer while protecting all sensitive information.

By overlaying an unencrypted base install with an encrypted filesystem via UnionFS, all changes made to a system are unreadable to an unauthorized user. This would include not only valuable personal or proprietary information, but any other data which may seem harmless, but as an aggregate provide more information about the users than they would like available to a thief or anybody else who might acquire physical access.

There exists the option for a duress password which would cause the encrypted partition to be overwritten seamlessly, presenting what appears to be a fresh install to the intruder.

At the moment, we do not have any scripts written. If you check the source tree, we do have fairly detailed instructions. We would be glad of any comments you might have.
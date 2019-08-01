Personal build for OnePlus 5T which I call as "SereneOS" forked from amazng "Project-Xtended" project.

Thank all the devs of Xtended and those devs & teams from whom kanged have been committed.

# ======== # ======== # ======== # ======== #

To initialize your local repository, use this command:

    repo init -u https://github.com/SereneOS/manifest -b xp

To sync the repository, use this command:

    repo sync -f -c -j8 --force-sync --no-clone-bundle --no-tags

To Build, use following commands:

1) . build/envsetup.sh
2) lunch xtended_dumpling-userdebug
3) make -j4 xtended

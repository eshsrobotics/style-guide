Gitignore
=========

Titles
------
Each section of the gitignore should be denoted by a title surrounded by hashes. There should be three spaces between the first hash on the left and the beginning of the title. There should also be three spaces before the last hash. If the title is not the first line of the document, then two blank lines should precede. A single blank line should always follow it.

Example:

    some other text
    
    
    ################
    #   My Title   #
    ################
    
    more text


Content
-------

Content should be between titles. The title should describe the purpose of the content.

Example:

    #############
    #   Title   #
    #############
    
    relevent content telling git what to ignore


Example
-------

    ############
    #   Java   #
    ############

    *.class

    # Package Files #
    *.jar
    *.war
    *.ear


    ###########
    #   GWT   #
    ###########

    *.class

    # Package Files #
    *.jar
    *.war

    # gwt caches and compiled units #
    war/gwt_bree/
    gwt-unitCache/

    # boilerplate generated classes #
    .apt_generated/

    # more caches and things from deploy #
    war/WEB-INF/deploy/
    war/WEB-INF/classes/


    #############
    #   Maven   #
    #############

    target/


    ###############
    #   Android   #
    ###############

    # built application files
    *.apk
    *.ap_

    # # files for the dex VM
    *.dex

    # # Java class files
    *.class

    # generated files
    bin/
    gen/

    # Local configuration file (sdk path, etc)
    local.properties

    # Eclipse project files
    .classpath
    .project

    # Proguard folder generated by Eclipse
    proguard/

=======
Install
=======

.. image:: https://img.shields.io/github/license/jcustenborder/kafka-connect-spooldir.svg

.. image:: https://img.shields.io/github/release/jcustenborder/kafka-connect-spooldir.svg
    :target: https://github.com/jcustenborder/kafka-connect-spooldir/releases

.. image:: https://img.shields.io/maven-central/v/com.github.jcustenborder.kafka.connect/kafka-connect-spooldir.svg
    :target: https://search.maven.org/#artifactdetails%7Ccom.github.jcustenborder.kafka.connect%7Ckafka-connect-spooldir%7C1.0-SNAPSHOT%7Cjar

^^^^^^^^^^^^^^^^
RPM Installation
^^^^^^^^^^^^^^^^

Before starting the RPM installation you must configure the :ref:`yum_repository` first.

.. code-block:: bash

    sudo yum install kafka-connect-spooldir


^^^^^^^^^^^^^^^^
DEB Installation
^^^^^^^^^^^^^^^^

Before starting the RPM installation you must configure the :ref:`apt_repository` first.

.. code-block:: bash

    sudo apt-get install kafka-connect-spooldir


^^^^^^^^^^^^^^^^^^
Maven Installation
^^^^^^^^^^^^^^^^^^

.. code-block:: xml

    <dependency>
        <groupId>com.github.jcustenborder.kafka.connect</groupId>
        <artifactId>kafka-connect-spooldir</artifactId>
        <version>1.0-SNAPSHOT</version>
    </dependency>



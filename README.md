Kafka base
=========

An ansible role which helps to download and unpack Kafka base.

Requirements
------------

None

Role Variables
--------------

kafka_root:      - root folder folder 
kafka_path:      - kafka path to install
kafka_tar_full:  - full name of kafka tar file
kafka_asc:       - full name of ASC file
kafka_tar_name:  - name of the file without extension
kafka_tar_local: - specifies local path to tar file if installed from local source
kafka_tar_uri:   - URI from where to downlaod tar file
kafka_keys_uri:  - URI from where to downlaod KEY
kafka_asc_uri:   - URI from where to downlaod ASC file
kafka_tmp_path:  - temporal place to where to download files

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: brokers
      roles:
         - ViacheslavIsaev.kafka-broker

License
-------

BSD

Author Information
------------------

Viacheslav Isaev has two decades of experience of distributed high payload systems development. He has been in charge of developing control systems for safety-critical facilities like railroads and particle accelerators, high-payload event processing systems for cybersecurity and mobile access points, introducing in house CI/CD practices. His hands-on experience incldues all stages of IT solutions development and operation. Vyacheslav’s interests lays in automation spectr either it is pure software or hardware-software solutions. Vyacheslav defines the key to success in 3 pillars  Domain Driven Design, Behavioral Driven and Test-Driven Development, which are standing on the foundation of Object Oriented Design and Clean Code practices.

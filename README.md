# mig-e2e
End to end tests for OCP Migration

* Run ```ansible-playbook mysql-pvc.yml``` for deploy, backup or restore the mysql example.
* Run ```ansible-playbook mysql-pvc-test.yml``` for testing your mysql:
    * Test of resources
    * Test of the data in the database

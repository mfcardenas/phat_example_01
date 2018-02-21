# PHAT Example Old people Home [01]
Older adult who lives alone in his home and performs different daily activities.

While doing the activities suffers falls at home.

<table style="border:none;">
    <tr>
        <td>
            <img height="80" width="80" src="https://github.com/mfcardenas/phat_examples/blob/master/img/in_progress.png" title="In progress"/>
        </td>
    <td>  
To run the demo

```
mvn clean compile
mvn exec:java -Dexec.mainClass=phat.OldPeopleHome
```
In case of running into memory problems
```
export MAVEN_OPTS="-Xmx512m -XX:MaxPermSize=128m"
```
And then run the previous command
    </td>
    <td>
        <img src="https://github.com/mfcardenas/phat_example_oph01/blob/master/img/img_older_people_home.png" />
    </td>
</tr>
</table>

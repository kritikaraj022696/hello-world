<?xml version="1.0" encoding="UTF-8"?>
<CustomObject xmlns="http://soap.sforce.com/2006/04/metadata">
    <actionOverrides>
        <actionName>Accept</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Accept</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Accept</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>CancelEdit</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>CancelEdit</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>CancelEdit</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Clone</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Clone</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Clone</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Delete</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Delete</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Delete</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Edit</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Edit</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Edit</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>List</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>List</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>List</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>New</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>New</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>New</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>SaveEdit</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>SaveEdit</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>SaveEdit</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Tab</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Tab</actionName>
        <formFactor>Large</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>Tab</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>View</actionName>
        <comment>Action override created by Lightning App Builder during activation.</comment>
        <content>Account_Contact_Role_Record_Page</content>
        <formFactor>Large</formFactor>
        <skipRecordTypeSelect>false</skipRecordTypeSelect>
        <type>Flexipage</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>View</actionName>
        <type>Default</type>
    </actionOverrides>
    <actionOverrides>
        <actionName>View</actionName>
        <formFactor>Small</formFactor>
        <type>Default</type>
    </actionOverrides>
    <allowInChatterGroups>false</allowInChatterGroups>
    <compactLayoutAssignment>SYSTEM</compactLayoutAssignment>
    <deploymentStatus>Deployed</deploymentStatus>
    <enableActivities>false</enableActivities>
    <enableBulkApi>true</enableBulkApi>
    <enableEnhancedLookup>false</enableEnhancedLookup>
    <enableFeeds>false</enableFeeds>
    <enableHistory>true</enableHistory>
    <enableLicensing>false</enableLicensing>
    <enableReports>true</enableReports>
    <enableSearch>true</enableSearch>
    <enableSharing>true</enableSharing>
    <enableStreamingApi>true</enableStreamingApi>
    <externalSharingModel>ControlledByParent</externalSharingModel>
    <fields>
        <fullName>AccountId__c</fullName>
        <externalId>false</externalId>
        <inlineHelpText>Account where the ACR will be displayed.</inlineHelpText>
        <label>Account</label>
        <referenceTo>Account</referenceTo>
        <relationshipLabel>Account Contact Roles</relationshipLabel>
        <relationshipName>Account_Contact_Roles</relationshipName>
        <relationshipOrder>0</relationshipOrder>
        <reparentableMasterDetail>false</reparentableMasterDetail>
        <trackHistory>true</trackHistory>
        <trackTrending>false</trackTrending>
        <type>MasterDetail</type>
        <writeRequiresMasterRead>true</writeRequiresMasterRead>
    </fields>
    <fields>
        <fullName>Account_Contact_Association__c</fullName>
        <caseSensitive>true</caseSensitive>
        <description>Case 01603606 - Concatenation of Account Id and Contact Id - to prevent duplicates</description>
        <externalId>false</externalId>
        <label>Account Contact Association</label>
        <length>100</length>
        <required>false</required>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Text</type>
        <unique>true</unique>
    </fields>
    <fields>
        <fullName>Account_Name__c</fullName>
        <externalId>false</externalId>
        <formula>AccountId__r.Name</formula>
        <formulaTreatBlanksAs>BlankAsZero</formulaTreatBlanksAs>
        <label>Account Name</label>
        <required>false</required>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Text</type>
        <unique>false</unique>
    </fields>
    <fields>
        <fullName>Community_URL_of_Record__c</fullName>
        <description>This field is used in community to create link for opening the record in enhanced related list</description>
        <externalId>false</externalId>
        <formula>HYPERLINK(&apos;/portal/s/accountcontactrole/&apos;&amp;Id, Name, &apos;_blank&apos;)</formula>
        <formulaTreatBlanksAs>BlankAsZero</formulaTreatBlanksAs>
        <label>Community URL of Record</label>
        <required>false</required>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Text</type>
        <unique>false</unique>
    </fields>
    <fields>
        <fullName>ContactId__c</fullName>
        <deleteConstraint>Restrict</deleteConstraint>
        <externalId>false</externalId>
        <inlineHelpText>Contact from this or other other accounts</inlineHelpText>
        <label>Contact</label>
        <lookupFilter>
            <active>false</active>
            <filterItems>
                <field>$Source.AccountId__c</field>
                <operation>equals</operation>
                <valueField>Contact.AccountId</valueField>
            </filterItems>
            <infoMessage>Only Contacts created under this account are shown, please click on &quot;Show all results&quot; to select a contact from a different account.</infoMessage>
            <isOptional>true</isOptional>
        </lookupFilter>
        <referenceTo>Contact</referenceTo>
        <relationshipLabel>Account Contact Roles</relationshipLabel>
        <relationshipName>Account_Contact_Roles</relationshipName>
        <required>false</required>
        <trackHistory>true</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Lookup</type>
    </fields>
    <fields>
        <fullName>Count_ACR_To_Service__c</fullName>
        <description>Sum of child ACR To Service</description>
        <externalId>false</externalId>
        <label>Count ACR To Service</label>
        <summaryForeignKey>ACR_to_Service__c.Account_Contact_Role__c</summaryForeignKey>
        <summaryOperation>count</summaryOperation>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Summary</type>
    </fields>
    <fields>
        <fullName>Default__c</fullName>
        <defaultValue>false</defaultValue>
        <description>Checked if contact role should be copy to opportunity.</description>
        <externalId>false</externalId>
        <inlineHelpText>Tick here where the Contact specified here should be copied to Opportunities as an Opportunity Contact Role.</inlineHelpText>
        <label>Default</label>
        <trackHistory>true</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Checkbox</type>
    </fields>
    <fields>
        <fullName>Email__c</fullName>
        <externalId>false</externalId>
        <formula>ContactId__r.Email</formula>
        <formulaTreatBlanksAs>BlankAsZero</formulaTreatBlanksAs>
        <label>Email</label>
        <required>false</required>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Text</type>
        <unique>false</unique>
    </fields>
    <fields>
        <fullName>IsGlobal__c</fullName>
        <externalId>false</externalId>
        <formula>Count_ACR_To_Service__c = 0</formula>
        <formulaTreatBlanksAs>BlankAsZero</formulaTreatBlanksAs>
        <inlineHelpText>If ticked this field means there are no specific relationships defined to Service(s). If role includes Maintenance or Emergency Contact, notifications for Incident or Change Cases will be sent to this person. Where specific services are related (non- Glob</inlineHelpText>
        <label>Is Global</label>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Checkbox</type>
    </fields>
    <fields>
        <fullName>IsPrimary__c</fullName>
        <defaultValue>false</defaultValue>
        <externalId>false</externalId>
        <inlineHelpText>Where there are several Account Contact roles with the same role, this identifies the main one to use. There is no system logic connected to this selection.</inlineHelpText>
        <label>Primary</label>
        <trackHistory>true</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Checkbox</type>
    </fields>
    <fields>
        <fullName>Is_Portal_User__c</fullName>
        <defaultValue>false</defaultValue>
        <description>01174228 Customer Portal Improvements - Contacts &amp; Cases</description>
        <externalId>false</externalId>
        <inlineHelpText>Controlling field for role multi.</inlineHelpText>
        <label>Is Portal User</label>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Checkbox</type>
    </fields>
    <fields>
        <fullName>Phone__c</fullName>
        <externalId>false</externalId>
        <formula>ContactId__r.Phone</formula>
        <formulaTreatBlanksAs>BlankAsZero</formulaTreatBlanksAs>
        <label>Phone</label>
        <required>false</required>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Text</type>
        <unique>false</unique>
    </fields>
    <fields>
        <fullName>Role_Multi__c</fullName>
        <externalId>false</externalId>
        <label>Role(s)</label>
        <required>false</required>
        <trackHistory>true</trackHistory>
        <trackTrending>false</trackTrending>
        <type>MultiselectPicklist</type>
        <valueSet>
            <controllingField>Is_Portal_User__c</controllingField>
            <valueSetDefinition>
                <sorted>true</sorted>
                <value>
                    <fullName>1st Level Service Escalation</fullName>
                    <default>false</default>
                    <label>1st Level Service Escalation</label>
                </value>
                <value>
                    <fullName>2nd Level Service Escalation</fullName>
                    <default>false</default>
                    <label>2nd Level Service Escalation</label>
                </value>
                <value>
                    <fullName>3rd Level Service Escalation</fullName>
                    <default>false</default>
                    <label>3rd Level Service Escalation</label>
                </value>
                <value>
                    <fullName>3rd Party</fullName>
                    <default>false</default>
                    <label>3rd Party</label>
                </value>
                <value>
                    <fullName>Abuse Contact</fullName>
                    <default>false</default>
                    <label>Abuse Contact</label>
                </value>
                <value>
                    <fullName>Authorised Approver</fullName>
                    <default>false</default>
                    <label>Authorised Approver</label>
                </value>
                <value>
                    <fullName>Billing Contact</fullName>
                    <default>false</default>
                    <label>Billing Contact</label>
                </value>
                <value>
                    <fullName>Business User</fullName>
                    <default>false</default>
                    <label>Business User</label>
                </value>
                <value>
                    <fullName>Decision Maker</fullName>
                    <default>false</default>
                    <label>Decision Maker</label>
                </value>
                <value>
                    <fullName>Economic Buyer</fullName>
                    <default>false</default>
                    <label>Economic Buyer</label>
                </value>
                <value>
                    <fullName>Economic Decision Maker</fullName>
                    <default>false</default>
                    <label>Economic Decision Maker</label>
                </value>
                <value>
                    <fullName>Emergency Contact</fullName>
                    <default>false</default>
                    <label>Emergency Contact</label>
                </value>
                <value>
                    <fullName>Evaluator</fullName>
                    <default>false</default>
                    <label>Evaluator</label>
                </value>
                <value>
                    <fullName>Executive Sponsor</fullName>
                    <default>false</default>
                    <label>Executive Sponsor</label>
                </value>
                <value>
                    <fullName>Grant Access</fullName>
                    <default>false</default>
                    <label>Grant Access</label>
                </value>
                <value>
                    <fullName>Influencer</fullName>
                    <default>false</default>
                    <label>Influencer</label>
                </value>
                <value>
                    <fullName>Legal Contact</fullName>
                    <default>false</default>
                    <label>Legal Contact</label>
                </value>
                <value>
                    <fullName>Maintenance Contact</fullName>
                    <default>false</default>
                    <label>Maintenance Contact</label>
                </value>
                <value>
                    <fullName>Only Access</fullName>
                    <default>false</default>
                    <label>Only Access</label>
                </value>
                <value>
                    <fullName>Other</fullName>
                    <default>false</default>
                    <label>Other</label>
                </value>
                <value>
                    <fullName>Partner - Accounting</fullName>
                    <default>false</default>
                    <label>Partner - Accounting</label>
                </value>
                <value>
                    <fullName>Partner - Legal</fullName>
                    <default>false</default>
                    <label>Partner - Legal</label>
                </value>
                <value>
                    <fullName>Partner - Managing Director</fullName>
                    <default>false</default>
                    <label>Partner - Managing Director</label>
                </value>
                <value>
                    <fullName>Partner - Operations</fullName>
                    <default>false</default>
                    <label>Partner - Operations</label>
                </value>
                <value>
                    <fullName>Partner - Sales</fullName>
                    <default>false</default>
                    <label>Partner - Sales</label>
                </value>
                <value>
                    <fullName>Technical Buyer</fullName>
                    <default>false</default>
                    <label>Technical Buyer</label>
                </value>
                <value>
                    <fullName>Technical Contact</fullName>
                    <default>false</default>
                    <label>Technical Contact</label>
                </value>
            </valueSetDefinition>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>1st Level Service Escalation</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>2nd Level Service Escalation</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>3rd Level Service Escalation</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>3rd Party</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Authorised Approver</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <controllingFieldValue>checked</controllingFieldValue>
                <valueName>Billing Contact</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Business User</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Decision Maker</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Economic Buyer</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Economic Decision Maker</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <controllingFieldValue>checked</controllingFieldValue>
                <valueName>Emergency Contact</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Evaluator</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Executive Sponsor</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Grant Access</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Influencer</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Legal Contact</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <controllingFieldValue>checked</controllingFieldValue>
                <valueName>Maintenance Contact</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Only Access</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Other</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Partner - Accounting</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Partner - Legal</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Partner - Managing Director</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Partner - Operations</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Partner - Sales</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <valueName>Technical Buyer</valueName>
            </valueSettings>
            <valueSettings>
                <controllingFieldValue>unchecked</controllingFieldValue>
                <controllingFieldValue>checked</controllingFieldValue>
                <valueName>Technical Contact</valueName>
            </valueSettings>
        </valueSet>
        <visibleLines>4</visibleLines>
    </fields>
    <fields>
        <fullName>isContainBillingRole__c</fullName>
        <description>Field used in Account object field &quot;# Billing Contacts&quot;.</description>
        <externalId>false</externalId>
        <formula>INCLUDES(Role_Multi__c, &apos;Billing Contact&apos;)</formula>
        <formulaTreatBlanksAs>BlankAsZero</formulaTreatBlanksAs>
        <label>isContainBillingRole</label>
        <trackHistory>false</trackHistory>
        <trackTrending>false</trackTrending>
        <type>Checkbox</type>
    </fields>
    <label>Account Contact Role</label>
    <nameField>
        <displayFormat>ACR-{00000000}</displayFormat>
        <label>Account Contact Role Name</label>
        <trackHistory>true</trackHistory>
        <type>AutoNumber</type>
    </nameField>
    <pluralLabel>Account Contact Roles</pluralLabel>
    <searchLayouts/>
    <sharingModel>ControlledByParent</sharingModel>
    <validationRules>
        <fullName>Add_Role</fullName>
        <active>true</active>
        <errorConditionFormula>ISBLANK( Role_Multi__c )</errorConditionFormula>
        <errorDisplayField>Role_Multi__c</errorDisplayField>
        <errorMessage>Add Role</errorMessage>
    </validationRules>
    <visibility>Public</visibility>
</CustomObject>

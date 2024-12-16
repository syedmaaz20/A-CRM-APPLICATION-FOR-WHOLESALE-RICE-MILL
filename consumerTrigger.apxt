trigger consumerTrigger on consumer__c (After insert) {
    if(trigger.isAfter && trigger.isInsert) {
        ConsumerRecord.sendEmailNotification(trigger.new);
    }
}

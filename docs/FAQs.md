![Documentation Home](https://github.com/lumagateinc/scheduler/blob/master/images/FAQs.png)

# Resource Scheduler FAQs

- [Can I apply VM to multiple schedules?](#can-i-apply-vm-to-multiple-schedules)</br>
- [How is Resource Scheduler licensed?](#how-is-sesource-scheduler-licensed)</br>
- [Where should I add the tag for scheduling VMs?](#Where-should-I-add-the-tag-for-scheduling-vms)</br>
- 
## Can I apply VM to multiple schedules?<!-- omit in toc -->

Yes, you can add a VM to multiples schedules through direct assignment or using tags. For step-by-instructions, see ["Managing Schedules"](https://github.com/lumagateinc/scheduler/#managing-schedules)

[back to top](#resource-scheduler-faqs)

## How is Resource Scheduler licensed?<!-- omit in toc -->

The Resource Scheduler for Microsoft Azure is licensed based on the number of VMs you intend to create schedules for. For pricing details, see ["Resource Scheduler Pricing"](https://lumagate.us/azure/pricing).

[back to top](#resource-scheduler-faqs)

## Where should I add the tag for scheduling VMs?<!-- omit in toc -->

To avoid confusion and unintentional scheduling of VMs, the Resource Scheduler only looks for tag name and value on the VM itself. Tags on the resource group are intentionally ignored.

[back to top](#resource-scheduler-faqs)
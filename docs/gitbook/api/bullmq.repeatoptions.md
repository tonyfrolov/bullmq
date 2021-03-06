<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [RepeatOptions](./bullmq.repeatoptions.md)

## RepeatOptions interface

Settings for repeatable jobs

<b>Signature:</b>

```typescript
export interface RepeatOptions 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [count?](./bullmq.repeatoptions.count.md) | number | <i>(Optional)</i> The start value for the repeat iteration count. |
|  [cron?](./bullmq.repeatoptions.cron.md) | string | <i>(Optional)</i> A cron pattern |
|  [endDate?](./bullmq.repeatoptions.enddate.md) | Date \| string \| number | <i>(Optional)</i> End date when the repeat job should stop repeating. |
|  [every?](./bullmq.repeatoptions.every.md) | number | <i>(Optional)</i> Repeat after this amount of milliseconds (<code>cron</code> setting cannot be used together with this setting.) |
|  [jobId?](./bullmq.repeatoptions.jobid.md) | string | <i>(Optional)</i> |
|  [limit?](./bullmq.repeatoptions.limit.md) | number | <i>(Optional)</i> Number of times the job should repeat at max. |
|  [prevMillis?](./bullmq.repeatoptions.prevmillis.md) | number | <i>(Optional)</i> |
|  [startDate?](./bullmq.repeatoptions.startdate.md) | Date \| string \| number | <i>(Optional)</i> Start date when the repeat job should start repeating (only with <code>cron</code>). |
|  [tz?](./bullmq.repeatoptions.tz.md) | string | <i>(Optional)</i> Timezone |


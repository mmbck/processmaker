---
description: Filter all Watchers in a ProcessMaker Screen to find that one you need.
---

# Search for a Watcher

## Search for a Watcher in a ProcessMaker Screen

Use the **Search** function to filter all Watchers from the **Watchers** screen. All Watchers in the **Watchers** screen may be used in the ProcessMaker Screen from which the **Watchers** screen displays.

{% hint style="info" %}
Your ProcessMaker user account or group membership must have the "Screens: View Screens" permission to search for Watchers in a ProcessMaker Screen unless your user account has the **Make this user a Super Admin** setting selected.

See the ProcessMaker [Screens](../../../../processmaker-administration/permission-descriptions-for-users-and-groups.md#screens) permissions or ask your ProcessMaker Administrator for assistance.
{% endhint %}

Follow these steps to search for a Watcher in a ProcessMaker Screen:

1. [View your ProcessMaker Screens.](../../manage-forms/view-all-forms.md) The **Screens** page displays.
2. [View the Watchers for a ProcessMaker Screen](view-watchers-for-a-screen.md#view-watchers-for-a-processmaker-screen). The **Watchers** screen displays.
3. Enter in the **Search** field the text to filter Watchers in that ProcessMaker Screens by using any of the following criteria:
   * **Name:** Filter by the Watcher name that displays in the **Name** column.
   * **Watching Variable:** Filter by the control in that ProcessMaker Screen from which the Watcher monitors for a change in its value by searching for that control's **Variable Name** value that displays in the **Watching Variable** column.
   * **Output Variable:** Filter by the control in that ProcessMaker Screen to which the Watcher outputs its action a control by searching for that control's **Variable Name** value that displays in the **Output Variable** column.
   * **Source:** Filter by the name of the [ProcessMaker Data Connector](../../../data-connector-management/what-is-a-data-connector.md) or [ProcessMaker Script](../../../scripts/what-is-a-script.md) from which the Watcher acts upon that displays in the **Source** column.

As you enter text into the **Search** field, Watchers display that match your entered text.

{% hint style="info" %}
If there are no search results, the following message displays: **No Results**.
{% endhint %}

## Related Topics



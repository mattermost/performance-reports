### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | avg | 21ms | 37ms | 16ms | 75.47
| ChannelStore.GetTeamChannels | avg | 16ms | 21ms | 5ms | 31.13
| ChannelStore.Autocomplete | avg | 35ms | 45ms | 10ms | 28.40
| PostStore.SearchPostsForUser | avg | 21ms | 25ms | 4ms | 18.78
| TeamStore.GetTotalMemberCount | avg | 33ms | 37ms | 4ms | 11.99
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.UpdateExpiredDNDStatuses | p99 | 6ms | 28ms | 22ms | 400.00
| ClusterDiscoveryStore.SetLastPingAt | p99 | 9ms | 28ms | 19ms | 210.53
| PostStore.GetPostReminderMetadata | p99 | 9ms | 23ms | 14ms | 150.48
| JobStore.UpdateOptimistically | p99 | 7ms | 17ms | 10ms | 137.93
| ChannelStore.Autocomplete | p99 | 175ms | 397ms | 222ms | 126.74
| ChannelStore.AutocompleteInTeamForSearch | p99 | 49ms | 99ms | 50ms | 101.39
| JobStore.Save | p99 | 9ms | 17ms | 8ms | 92.75
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.CreateDirectChannel | p99 | 45ms | 80ms | 35ms | 77.99
| DraftStore.GetDraftsForUser | p99 | 5ms | 8ms | 3ms | 60.16
| PostStore.SearchPostsForUser | p99 | 407ms | 602ms | 195ms | 47.85
| UserStore.IsEmpty | p99 | 13ms | 16ms | 3ms | 22.40
| GroupStore.GetGroups | p99 | 14ms | 16ms | 2ms | 14.18
| UserStore.UpdateFailedPasswordAttempts | p99 | 25ms | 28ms | 3ms | 11.82
| ThreadStore.MaintainMembership | p99 | 18ms | 20ms | 2ms | 10.83
| ThreadStore.GetTotalThreads | p99 | 20ms | 22ms | 2ms | 9.90
| ChannelStore.GetPublicChannelsForTeam | p99 | 42ms | 46ms | 4ms | 9.61
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 36ms | 39ms | 3ms | 8.28
| ChannelStore.CreateInitialSidebarCategories | p99 | 78ms | 84ms | 6ms | 7.70
| ProductNoticesStore.View | p99 | 194ms | 208ms | 14ms | 7.23
| ChannelStore.SaveMember | p99 | 131ms | 140ms | 9ms | 6.88
| PreferenceStore.Save | p99 | 65ms | 69ms | 4ms | 6.14
| TeamStore.SaveMember | p99 | 83ms | 86ms | 3ms | 3.62
| UserStore.AutocompleteUsersInChannel | p99 | 168ms | 173ms | 5ms | 2.97
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -102.19
| ChannelStore.GetMany | avg | 5ms | 2ms | -3ms | -58.71
| PostStore.SetPostReminder | avg | 8ms | 6ms | -2ms | -23.59
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetMany | p99 | 25ms | 5ms | -20ms | -81.46
| PostStore.SetPostReminder | p99 | 47ms | 10ms | -37ms | -79.14
| UserStore.GetMany | p99 | 22ms | 5ms | -17ms | -78.34
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 22ms | 5ms | -17ms | -76.23
| FileInfoStore.GetByIds | p99 | 14ms | 5ms | -9ms | -64.40
| JobStore.GetCountByStatusAndType | p99 | 16ms | 7ms | -9ms | -54.71
| StatusStore.SaveOrUpdateMany | p99 | 81ms | 37ms | -44ms | -54.43
| PostStore.GetPostReminders | p99 | 10ms | 5ms | -5ms | -52.36
| FileInfoStore.AttachToPost | p99 | 21ms | 10ms | -11ms | -52.34
| FileInfoStore.SetContent | p99 | 38ms | 20ms | -18ms | -47.37
| PostStore.GetPostsAfter | p99 | 9ms | 5ms | -4ms | -44.69
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 9ms | 5ms | -4ms | -43.96
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.72
| JobStore.GetNewestJobByStatusesAndType | p99 | 9ms | 5ms | -4ms | -43.01
| FileInfoStore.Save | p99 | 23ms | 15ms | -8ms | -35.33
| JobStore.UpdateStatus | p99 | 7ms | 5ms | -2ms | -27.59
| ChannelStore.Save | p99 | 33ms | 24ms | -9ms | -27.27
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 123ms | 91ms | -32ms | -25.96
| ReactionStore.GetForPost | p99 | 12ms | 10ms | -2ms | -16.15
| UserStore.Update | p99 | 19ms | 16ms | -3ms | -15.92
| ChannelStore.GetChannels | p99 | 17ms | 15ms | -2ms | -12.09
| ChannelStore.GetMemberForPost | p99 | 17ms | 15ms | -2ms | -12.07
| ChannelStore.SearchGroupChannels | p99 | 20ms | 18ms | -2ms | -10.15
| PropertyFieldStore.SearchPropertyFields | p99 | 24ms | 22ms | -2ms | -8.44
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | avg | 1ms | 3ms | 2ms | 180.52
| autocompleteChannelsForTeamForSearch | avg | 21ms | 37ms | 16ms | 75.23
| searchAllChannels | avg | 35ms | 45ms | 10ms | 28.24
| getTeamStats | avg | 34ms | 38ms | 4ms | 11.84
| searchPostsInTeam | avg | 29ms | 32ms | 3ms | 10.47
| createGroupChannel | avg | 252ms | 266ms | 14ms | 5.56
| removeUserCustomStatus | avg | 112ms | 117ms | 5ms | 4.46
| addTeamMember | avg | 618ms | 625ms | 7ms | 1.13
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchAllChannels | p99 | 175ms | 397ms | 222ms | 126.74
| autocompleteChannelsForTeamForSearch | p99 | 49ms | 99ms | 50ms | 101.29
| listCPAValues | p99 | 10ms | 18ms | 8ms | 80.99
| listCPAFields | p99 | 25ms | 43ms | 18ms | 72.01
| getDrafts | p99 | 5ms | 8ms | 3ms | 60.16
| getTeamMember | p99 | 9ms | 14ms | 5ms | 52.63
| searchPostsInTeam | p99 | 407ms | 602ms | 195ms | 47.85
| root | p99 | 36ms | 44ms | 8ms | 22.54
| getChannelMembersForTeamForUser | p99 | 16ms | 18ms | 2ms | 12.24
| getPublicChannelsForTeam | p99 | 42ms | 46ms | 4ms | 9.61
| getTeamScheduledPosts | p99 | 37ms | 40ms | 3ms | 8.18
| getUser | p99 | 38ms | 40ms | 2ms | 5.30
| autocompleteUsers | p99 | 141ms | 145ms | 4ms | 2.83
| addTeamMember | p99 | 2.212s | 2.266s | 54ms | 2.44
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 3ms | 0s | -3ms | -92.07
| createChannelBookmark | avg | 16ms | 13ms | -3ms | -18.60
| setPostReminder | avg | 19ms | 16ms | -3ms | -15.51
| createChannel | avg | 202ms | 177ms | -25ms | -12.38
| getProfileImage | avg | 100ms | 91ms | -9ms | -9.01
| createDirectChannel | avg | 172ms | 164ms | -8ms | -4.65
| uploadFileStream | avg | 425ms | 418ms | -7ms | -1.65
| addChannelMember | avg | 168ms | 166ms | -2ms | -1.19
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| setPostReminder | p99 | 94ms | 25ms | -69ms | -73.80
| getChannel | p99 | 10ms | 5ms | -5ms | -51.33
| updateReadStateThreadByUser | p99 | 72ms | 59ms | -13ms | -18.16
| createDirectChannel | p99 | 455ms | 405ms | -50ms | -10.99
| patchPost | p99 | 50ms | 45ms | -5ms | -10.06
| updatePreferences | p99 | 20ms | 18ms | -2ms | -10.04
| saveReaction | p99 | 27ms | 25ms | -2ms | -7.28
| getUsers | p99 | 36ms | 34ms | -2ms | -5.55
| addChannelMember | p99 | 362ms | 346ms | -16ms | -4.41
| getProfileImage | p99 | 466ms | 454ms | -12ms | -2.57
| getFileThumbnail | p99 | 97ms | 95ms | -2ms | -2.07
| getFilePreview | p99 | 98ms | 96ms | -2ms | -2.05
| login | p99 | 543ms | 533ms | -10ms | -1.84
| getPostsForChannel | p99 | 169ms | 166ms | -3ms | -1.78
| createPost | p99 | 742ms | 729ms | -13ms | -1.75
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.716
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.457
| ChannelBookmarkStore.Save |  Avg| 10ms| 9ms | -1ms | -10.185
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.822
| ChannelStore.Autocomplete |  Avg| 35ms| 45ms | 10ms | 28.403
| |  P99| 175ms| 397ms | 222ms | 126.738
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 21ms| 37ms | 16ms | 75.468
| |  P99| 49ms| 99ms | 50ms | 101.394
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 19ms | 1ms | 5.516
| |  P99| 45ms| 80ms | 35ms | 77.994
| ChannelStore.CreateInitialSidebarCategories |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 78ms| 84ms | 6ms | 7.703
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 123ms| 91ms | -32ms | -25.964
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 40ms| 40ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 1ms| 2ms | 1ms | 69.521
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -12.091
| ChannelStore.GetChannelsByUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.980
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.974
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 27ms | -1ms | -3.523
| ChannelStore.GetMany |  Avg| 5ms| 2ms | -3ms | -58.710
| |  P99| 25ms| 5ms | -20ms | -81.465
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 15ms | -2ms | -12.073
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -102.187
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.209
| ChannelStore.GetMembersForUserWithPagination |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.261
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 42ms| 46ms | 4ms | 9.610
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 36ms| 39ms | 3ms | 8.283
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 6ms | -1ms | -14.142
| |  P99| 24ms| 23ms | -1ms | -4.094
| ChannelStore.GetTeamChannels |  Avg| 16ms| 21ms | 5ms | 31.128
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 5.122
| ChannelStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 33ms| 24ms | -9ms | -27.273
| ChannelStore.SaveMember |  Avg| 28ms| 29ms | 1ms | 3.532
| |  P99| 131ms| 140ms | 9ms | 6.880
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -10.154
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 28ms| 29ms | 1ms | 3.561
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 28ms | 19ms | 210.525
| CommandWebhookStore.Cleanup |  Avg| 1ms| 2ms | 1ms | 67.015
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 3ms | -1ms | -28.499
| |  P99| 9ms| 10ms | 1ms | 10.582
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.162
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 8.826
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 5ms | -1ms | -17.456
| |  P99| 21ms| 10ms | -11ms | -52.339
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 1ms | -1ms | -59.002
| |  P99| 14ms| 5ms | -9ms | -64.404
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 15ms | -8ms | -35.329
| FileInfoStore.SetContent |  Avg| 7ms| 6ms | -1ms | -14.681
| |  P99| 38ms| 20ms | -18ms | -47.369
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.406
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 16ms | 2ms | 14.179
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 7ms | -9ms | -54.711
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.011
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 17ms | 8ms | 92.754
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 17ms | 10ms | 137.931
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -27.586
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPostWithContext |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 269ms| 267ms | -2ms | -0.743
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 12ms| 11ms | -1ms | -8.050
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.249
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.304
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 23ms | 14ms | 150.478
| PostStore.GetPostReminders |  Avg| 3ms| 2ms | -1ms | -38.206
| |  P99| 10ms| 5ms | -5ms | -52.356
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.422
| PostStore.GetPostsAfter |  Avg| 3ms| 2ms | -1ms | -38.475
| |  P99| 9ms| 5ms | -4ms | -44.693
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.814
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.198
| PostStore.SearchPostsForUser |  Avg| 21ms| 25ms | 4ms | 18.782
| |  P99| 407ms| 602ms | 195ms | 47.853
| PostStore.SetPostReminder |  Avg| 8ms| 6ms | -2ms | -23.587
| |  P99| 47ms| 10ms | -37ms | -79.144
| PostStore.Update |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 1ms | -1ms | -66.418
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 65ms| 69ms | 4ms | 6.145
| ProductNoticesStore.ClearOldNotices |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 35ms| 36ms | 1ms | 2.820
| |  P99| 194ms| 208ms | 14ms | 7.228
| PropertyFieldStore.SearchPropertyFields |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 22ms | -2ms | -8.436
| PropertyValueStore.SearchPropertyValues |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.154
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 3ms | 1ms | 40.162
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -76.233
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.728
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.956
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 43ms| 44ms | 1ms | 2.307
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 3ms | 1ms | 42.057
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 37ms| 36ms | -1ms | -2.688
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 3ms| 4ms | 1ms | 29.629
| |  P99| 23ms| 22ms | -1ms | -4.321
| StatusStore.SaveOrUpdateMany |  Avg| 9ms| 8ms | -1ms | -11.322
| |  P99| 81ms| 37ms | -44ms | -54.433
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 3ms | 1ms | 60.930
| |  P99| 6ms| 28ms | 22ms | 400.000
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.268
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.018
| TeamStore.GetActiveMemberCount |  Avg| 34ms| 35ms | 1ms | 2.967
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.467
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 33ms| 37ms | 4ms | 11.991
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 22ms| 23ms | 1ms | 4.484
| |  P99| 83ms| 86ms | 3ms | 3.619
| TemporaryPostStore.GetExpiredPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.203
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.211
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 22ms | 2ms | 9.901
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.397
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.970
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.999
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.834
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.010
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.463
| TokenStore.Cleanup |  Avg| 1ms| 2ms | 1ms | 71.750
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 1ms | -1ms | -62.322
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 34ms| 35ms | 1ms | 2.905
| |  P99| 168ms| 173ms | 5ms | 2.973
| UserStore.Count |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.676
| UserStore.GetAllProfilesInChannel |  Avg| 157ms| 157ms | 0s | 0.000
| |  P99| 480ms| 481ms | 1ms | 0.208
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 22ms| 5ms | -17ms | -78.342
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 16ms | 3ms | 22.403
| UserStore.Save |  Avg| 134ms| 134ms | 0s | 0.000
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.Search |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -15.916
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 25ms| 28ms | 3ms | 11.822
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 23ms | -1ms | -4.227
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 4ms | 1ms | 28.720
| |  P99| 23ms| 24ms | 1ms | 4.319
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 168ms| 166ms | -2ms | -1.193
| | P99| 362ms| 346ms | -16ms | -4.414
| addTeamMember | Avg| 618ms| 625ms | 7ms | 1.133
| | P99| 2.212s| 2.266s | 54ms | 2.441
| autocompleteChannelsForTeamForSearch | Avg| 21ms| 37ms | 16ms | 75.229
| | P99| 49ms| 99ms | 50ms | 101.285
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 141ms| 145ms | 4ms | 2.833
| createChannel | Avg| 202ms| 177ms | -25ms | -12.384
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 16ms| 13ms | -3ms | -18.600
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 172ms| 164ms | -8ms | -4.647
| | P99| 455ms| 405ms | -50ms | -10.989
| createGroupChannel | Avg| 252ms| 266ms | 14ms | 5.563
| | P99| 495ms| 496ms | 1ms | 0.202
| createPost | Avg| 148ms| 149ms | 1ms | 0.674
| | P99| 742ms| 729ms | -13ms | -1.752
| createSchedulePost | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.102
| createUser | Avg| 202ms| 203ms | 1ms | 0.495
| | P99| 488ms| 491ms | 3ms | 0.614
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| deletePost | Avg| 17ms| 16ms | -1ms | -5.842
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 9ms | -1ms | -10.494
| | P99| 24ms| 24ms | 0s | 0.000
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 40ms| 41ms | 1ms | 2.507
| getChannel | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 5ms | -5ms | -51.334
| getChannelMember | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 47ms| 47ms | 0s | 0.000
| getChannelMembers | Avg| 3ms| 0s | -3ms | -92.074
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 18ms | 2ms | 12.238
| getChannelMembersForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 29ms| 30ms | 1ms | 3.451
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 17ms| 16ms | -1ms | -6.003
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.251
| getClientConfig | Avg| 6ms| 7ms | 1ms | 15.578
| | P99| 48ms| 48ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.162
| getFilePreview | Avg| 42ms| 41ms | -1ms | -2.398
| | P99| 98ms| 96ms | -2ms | -2.046
| getFileThumbnail | Avg| 40ms| 40ms | 0s | 0.000
| | P99| 97ms| 95ms | -2ms | -2.070
| getPostThread | Avg| 10ms| 9ms | -1ms | -10.357
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 19ms| 19ms | 0s | 0.000
| | P99| 169ms| 166ms | -3ms | -1.780
| getPostsForChannelAroundLastUnread | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 91ms| 92ms | 1ms | 1.095
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 24ms | -1ms | -4.025
| getProfileImage | Avg| 100ms| 91ms | -9ms | -9.006
| | P99| 466ms| 454ms | -12ms | -2.574
| getPublicChannelsForTeam | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 42ms| 46ms | 4ms | 9.610
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 14ms | 5ms | 52.633
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 37ms| 40ms | 3ms | 8.179
| getTeamStats | Avg| 34ms| 38ms | 4ms | 11.836
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 39ms| 38ms | -1ms | -2.536
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 23ms | 1ms | 4.536
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 38ms| 40ms | 2ms | 5.298
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 36ms| 34ms | -2ms | -5.546
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 3ms| 4ms | 1ms | 39.752
| | P99| 25ms| 43ms | 18ms | 72.008
| listCPAValues | Avg| 2ms| 3ms | 1ms | 54.183
| | P99| 10ms| 18ms | 8ms | 80.995
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 10ms | 1ms | 11.020
| login | Avg| 111ms| 110ms | -1ms | -0.905
| | P99| 543ms| 533ms | -10ms | -1.843
| logout | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| patchPost | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 50ms| 45ms | -5ms | -10.060
| removeUserCustomStatus | Avg| 112ms| 117ms | 5ms | 4.459
| | P99| 247ms| 248ms | 1ms | 0.405
| root | Avg| 1ms| 3ms | 2ms | 180.517
| | P99| 36ms| 44ms | 8ms | 22.535
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 27ms| 25ms | -2ms | -7.282
| searchAllChannels | Avg| 35ms| 45ms | 10ms | 28.243
| | P99| 175ms| 397ms | 222ms | 126.738
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 20ms | 0s | 0.000
| searchPostsInTeam | Avg| 29ms| 32ms | 3ms | 10.474
| | P99| 407ms| 602ms | 195ms | 47.853
| searchUsers | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 19ms| 16ms | -3ms | -15.505
| | P99| 94ms| 25ms | -69ms | -73.796
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 44ms| 43ms | -1ms | -2.259
| | P99| 97ms| 97ms | 0s | 0.000
| updatePreferences | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 20ms| 18ms | -2ms | -10.042
| updateReadStateAllThreadsByUser | Avg| 4ms| 3ms | -1ms | -28.097
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 72ms| 59ms | -13ms | -18.156
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 425ms| 418ms | -7ms | -1.646
| | P99| 992ms| 987ms | -5ms | -0.504
| upsertDraft | Avg| 3ms| 4ms | 1ms | 28.803
| | P99| 15ms| 15ms | 0s | 0.000
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 32ms| 32ms | 0s | 0.000

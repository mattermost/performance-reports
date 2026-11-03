### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.AnalyticsPostCount | avg | 569ms | 752ms | 183ms | 32.15
| PostStore.Delete | avg | 13ms | 15ms | 2ms | 15.10
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.Save | p99 | 5ms | 16ms | 11ms | 222.22
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.SearchGroupChannels | p99 | 14ms | 20ms | 6ms | 44.00
| UserStore.Update | p99 | 17ms | 21ms | 4ms | 23.67
| ChannelStore.AutocompleteInTeamForSearch | p99 | 645ms | 653ms | 8ms | 1.24
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -116.15
| ThreadStore.MarkAllAsReadByTeam | avg | 4ms | 2ms | -2ms | -46.04
| PostStore.SearchPostsForUser | avg | 173ms | 142ms | -31ms | -17.92
| ChannelStore.GetTeamChannels | avg | 37ms | 33ms | -4ms | -10.92
| UserStore.GetAllProfilesInChannel | avg | 124ms | 117ms | -7ms | -5.63
| UserStore.Save | avg | 107ms | 105ms | -2ms | -1.87
| ChannelStore.Autocomplete | avg | 389ms | 385ms | -4ms | -1.03
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| StatusStore.UpdateExpiredDNDStatuses | p99 | 18ms | 5ms | -13ms | -71.23
| ChannelStore.GetTeamChannels | p99 | 98ms | 50ms | -48ms | -49.23
| ScheduledPostStore.CreateScheduledPost | p99 | 9ms | 5ms | -4ms | -44.94
| PostStore.GetPostReminders | p99 | 9ms | 5ms | -4ms | -43.96
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -43.96
| StatusStore.SaveOrUpdateMany | p99 | 30ms | 20ms | -10ms | -33.33
| ThreadStore.MarkAsRead | p99 | 7ms | 5ms | -2ms | -30.69
| ThreadStore.UpdateMembership | p99 | 7ms | 5ms | -2ms | -30.23
| SessionStore.Get | p99 | 14ms | 10ms | -4ms | -29.58
| ChannelStore.GetByName | p99 | 14ms | 10ms | -4ms | -29.56
| JobStore.UpdateStatusOptimistically | p99 | 7ms | 5ms | -2ms | -28.17
| UserStore.Count | p99 | 15ms | 11ms | -4ms | -27.26
| DraftStore.Upsert | p99 | 8ms | 6ms | -2ms | -26.10
| SessionStore.UpdateLastActivityAt | p99 | 8ms | 6ms | -2ms | -25.34
| ChannelStore.CreateInitialSidebarCategories | p99 | 33ms | 25ms | -8ms | -24.20
| StatusStore.SaveOrUpdate | p99 | 9ms | 7ms | -2ms | -23.39
| WebhookStore.GetOutgoingByTeam | p99 | 15ms | 12ms | -3ms | -20.35
| FileInfoStore.AttachToPost | p99 | 12ms | 10ms | -2ms | -16.68
| ThreadStore.MaintainMembership | p99 | 12ms | 10ms | -2ms | -16.56
| PostStore.Get | p99 | 13ms | 11ms | -2ms | -14.88
| FileInfoStore.SetContent | p99 | 19ms | 17ms | -2ms | -10.36
| UserStore.GetAllProfilesInChannel | p99 | 464ms | 431ms | -33ms | -7.11
| UserStore.AutocompleteUsersInChannel | p99 | 154ms | 149ms | -5ms | -3.24
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | avg | 23ms | 29ms | 6ms | 25.97
| patchPost | avg | 29ms | 31ms | 2ms | 6.83
| autocompleteChannelsForTeamForSearch | avg | 34ms | 36ms | 2ms | 5.89
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| logout | p99 | 25ms | 50ms | 25ms | 100.57
| searchPostsInTeam | p99 | 997ms | 1.948s | 951ms | 95.43
| setPostReminder | p99 | 25ms | 48ms | 23ms | 92.52
| searchPostsInAllTeams | p99 | 1.9s | 3.481s | 1.581s | 83.21
| deletePost | p99 | 25ms | 45ms | 20ms | 80.47
| patchPost | p99 | 215ms | 365ms | 150ms | 69.85
| searchGroupChannels | p99 | 15ms | 20ms | 5ms | 32.40
| unfollowThreadByUser | p99 | 25ms | 30ms | 5ms | 20.12
| getPostsForChannel | p99 | 137ms | 154ms | 17ms | 12.44
| autocompleteChannelsForTeamForSearch | p99 | 645ms | 653ms | 8ms | 1.24
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 4ms | 0s | -4ms | -112.72
| getProfileImage | avg | 89ms | 31ms | -58ms | -64.95
| updateReadStateAllThreadsByUser | avg | 5ms | 2ms | -3ms | -64.21
| getPostsForChannelAroundLastUnread | avg | 433ms | 354ms | -79ms | -18.26
| searchPostsInTeam | avg | 164ms | 152ms | -12ms | -7.30
| addChannelMember | avg | 275ms | 261ms | -14ms | -5.09
| login | avg | 133ms | 127ms | -6ms | -4.50
| addTeamMember | avg | 621ms | 595ms | -26ms | -4.19
| createChannel | avg | 327ms | 318ms | -9ms | -2.75
| createGroupChannel | avg | 633ms | 616ms | -17ms | -2.69
| createPost | avg | 113ms | 110ms | -3ms | -2.66
| uploadFileStream | avg | 442ms | 434ms | -8ms | -1.81
| createUser | avg | 118ms | 116ms | -2ms | -1.70
| removeUserCustomStatus | avg | 231ms | 228ms | -3ms | -1.30
| searchAllChannels | avg | 390ms | 385ms | -5ms | -1.28
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| createSchedulePost | p99 | 22ms | 10ms | -12ms | -55.25
| getProfileImage | p99 | 435ms | 240ms | -195ms | -44.83
| getChannelsForUser | p99 | 7ms | 5ms | -2ms | -30.56
| getChannel | p99 | 9ms | 7ms | -2ms | -23.49
| getTeamsUnreadForUser | p99 | 13ms | 11ms | -2ms | -15.08
| getChannelMember | p99 | 21ms | 18ms | -3ms | -14.49
| autocompleteUsers | p99 | 129ms | 121ms | -8ms | -6.18
| getUsers | p99 | 199ms | 190ms | -9ms | -4.52
| getPostsForChannelAroundLastUnread | p99 | 9.216s | 9.011s | -205ms | -2.22
| createPost | p99 | 469ms | 464ms | -5ms | -1.07
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 4ms | 1ms | 28.791
| |  P99| 8ms| 7ms | -1ms | -12.976
| BotStore.Get |  Avg| 2ms| 1ms | -1ms | -48.105
| |  P99| 9ms| 5ms | -4ms | -43.956
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 4ms | 1ms | 28.845
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 389ms| 385ms | -4ms | -1.028
| |  P99| 987ms| 986ms | -1ms | -0.101
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 34ms| 35ms | 1ms | 2.968
| |  P99| 645ms| 653ms | 8ms | 1.240
| ChannelStore.CreateDirectChannel |  Avg| 21ms| 20ms | -1ms | -4.836
| |  P99| 46ms| 45ms | -1ms | -2.167
| ChannelStore.CreateInitialSidebarCategories |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 33ms| 25ms | -8ms | -24.199
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.519
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 31ms| 30ms | -1ms | -3.258
| ChannelStore.GetBoardChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -29.565
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.747
| ChannelStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -15.498
| ChannelStore.GetMemberCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -116.149
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.479
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 37ms| 33ms | -4ms | -10.917
| |  P99| 98ms| 50ms | -48ms | -49.231
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 26ms| 25ms | -1ms | -3.908
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 4ms | 1ms | 29.246
| |  P99| 14ms| 20ms | 6ms | 43.996
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 30ms| 29ms | -1ms | -3.341
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.234
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 4ms| 3ms | -1ms | -28.537
| |  P99| 8ms| 6ms | -2ms | -26.102
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.677
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.494
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.363
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.417
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.090
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 16ms | 11ms | 222.222
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.091
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.169
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.982
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPostWithContext |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 569ms| 752ms | 183ms | 32.151
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 13ms| 15ms | 2ms | 15.097
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -14.880
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.328
| PostStore.GetPostReminders |  Avg| 3ms| 2ms | -1ms | -38.887
| |  P99| 9ms| 5ms | -4ms | -43.956
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 30ms| 30ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 1ms | -1ms | -66.247
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetVisiblePostIdAroundTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 46ms| 47ms | 1ms | 2.177
| PostStore.SearchPostsForUser |  Avg| 173ms| 142ms | -31ms | -17.924
| |  P99| 996ms| 995ms | -1ms | -0.100
| PostStore.SetPostReminder |  Avg| 6ms| 7ms | 1ms | 15.403
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PropertyFieldStore.GetForGroup |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.461
| PropertyFieldStore.SearchPropertyFields |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PropertyGroupStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PropertyValueStore.SearchPropertyValues |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.CreateScheduledPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.944
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -29.582
| SessionStore.GetLRUSessions |  Avg| 2ms| 1ms | -1ms | -66.244
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -25.337
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 4ms| 3ms | -1ms | -27.934
| |  P99| 9ms| 7ms | -2ms | -23.392
| StatusStore.SaveOrUpdateMany |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 30ms| 20ms | -10ms | -33.334
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 5ms | -13ms | -71.233
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -16.383
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.231
| TemporaryPostStore.GetExpiredPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.985
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.239
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.587
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.561
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 2ms | -1ms | -36.959
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 4ms| 2ms | -2ms | -46.036
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.693
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.232
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 1ms | -1ms | -63.042
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 154ms| 149ms | -5ms | -3.240
| UserStore.Count |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 15ms| 11ms | -4ms | -27.264
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 124ms| 117ms | -7ms | -5.627
| |  P99| 464ms| 431ms | -33ms | -7.114
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 96ms| 95ms | -1ms | -1.042
| |  P99| 242ms| 241ms | -1ms | -0.412
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 107ms| 105ms | -2ms | -1.865
| |  P99| 248ms| 248ms | 0s | 0.000
| UserStore.Search |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| UserStore.TryIncrementFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.555
| UserStore.Update |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 17ms| 21ms | 4ms | 23.668
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -20.353
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 275ms| 261ms | -14ms | -5.086
| | P99| 497ms| 496ms | -1ms | -0.201
| addTeamMember | Avg| 621ms| 595ms | -26ms | -4.187
| | P99| 996ms| 994ms | -2ms | -0.201
| autocompleteChannelsForTeamForSearch | Avg| 34ms| 36ms | 2ms | 5.886
| | P99| 645ms| 653ms | 8ms | 1.240
| autocompleteUsers | Avg| 26ms| 26ms | 0s | 0.000
| | P99| 129ms| 121ms | -8ms | -6.178
| createChannel | Avg| 327ms| 318ms | -9ms | -2.751
| | P99| 498ms| 497ms | -1ms | -0.201
| createDirectChannel | Avg| 429ms| 425ms | -4ms | -0.933
| | P99| 961ms| 959ms | -2ms | -0.208
| createGroupChannel | Avg| 633ms| 616ms | -17ms | -2.685
| | P99| 994ms| 994ms | 0s | 0.000
| createPost | Avg| 113ms| 110ms | -3ms | -2.663
| | P99| 469ms| 464ms | -5ms | -1.067
| createSchedulePost | Avg| 5ms| 4ms | -1ms | -21.195
| | P99| 22ms| 10ms | -12ms | -55.253
| createUser | Avg| 118ms| 116ms | -2ms | -1.695
| | P99| 249ms| 249ms | 0s | 0.000
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| deletePost | Avg| 20ms| 21ms | 1ms | 5.112
| | P99| 25ms| 45ms | 20ms | 80.472
| followThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 11ms| 10ms | -1ms | -9.025
| getChannel | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 9ms| 7ms | -2ms | -23.495
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 21ms| 18ms | -3ms | -14.485
| getChannelMembers | Avg| 4ms| 0s | -4ms | -112.719
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getChannelStats | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -30.556
| getClientConfig | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 17ms| 16ms | -1ms | -5.888
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -17.345
| getFilePreview | Avg| 45ms| 45ms | 0s | 0.000
| | P99| 99ms| 99ms | 0s | 0.000
| getFileThumbnail | Avg| 42ms| 43ms | 1ms | 2.355
| | P99| 98ms| 99ms | 1ms | 1.020
| getPostThread | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getPostsForChannel | Avg| 16ms| 16ms | 0s | 0.000
| | P99| 137ms| 154ms | 17ms | 12.440
| getPostsForChannelAroundLastUnread | Avg| 433ms| 354ms | -79ms | -18.258
| | P99| 9.216s| 9.011s | -205ms | -2.224
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.725
| getProfileImage | Avg| 89ms| 31ms | -58ms | -64.955
| | P99| 435ms| 240ms | -195ms | -44.828
| getPublicChannelsForTeam | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getTeamStats | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 11ms | -2ms | -15.077
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 13ms | -1ms | -7.272
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -13.183
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 199ms| 190ms | -9ms | -4.520
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 133ms| 127ms | -6ms | -4.503
| | P99| 249ms| 248ms | -1ms | -0.402
| logout | Avg| 23ms| 29ms | 6ms | 25.971
| | P99| 25ms| 50ms | 25ms | 100.568
| patchPost | Avg| 29ms| 31ms | 2ms | 6.830
| | P99| 215ms| 365ms | 150ms | 69.849
| removeUserCustomStatus | Avg| 231ms| 228ms | -3ms | -1.298
| | P99| 494ms| 493ms | -1ms | -0.202
| root | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 7ms | -1ms | -12.911
| saveReaction | Avg| 24ms| 24ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| searchAllChannels | Avg| 390ms| 385ms | -5ms | -1.283
| | P99| 987ms| 987ms | 0s | 0.000
| searchGroupChannels | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 15ms| 20ms | 5ms | 32.401
| searchPostsInAllTeams | Avg| 226ms| 227ms | 1ms | 0.442
| | P99| 1.9s| 3.481s | 1.581s | 83.210
| searchPostsInTeam | Avg| 164ms| 152ms | -12ms | -7.305
| | P99| 997ms| 1.948s | 951ms | 95.433
| searchUsers | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 49ms| 49ms | 0s | 0.000
| setPostReminder | Avg| 22ms| 22ms | 0s | 0.000
| | P99| 25ms| 48ms | 23ms | 92.515
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 25ms| 30ms | 5ms | 20.121
| updateCategoriesForTeamForUser | Avg| 43ms| 42ms | -1ms | -2.351
| | P99| 50ms| 50ms | 0s | 0.000
| updatePreferences | Avg| 8ms| 9ms | 1ms | 11.769
| | P99| 20ms| 21ms | 1ms | 4.922
| updateReadStateAllThreadsByUser | Avg| 5ms| 2ms | -3ms | -64.213
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 50ms| 49ms | -1ms | -2.020
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 442ms| 434ms | -8ms | -1.810
| | P99| 994ms| 995ms | 1ms | 0.101
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000

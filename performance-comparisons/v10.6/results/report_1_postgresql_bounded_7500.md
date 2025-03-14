### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.GetMultipleByName | avg | 2ms | 5ms | 3ms | 176.11
| TeamStore.GetTotalMemberCount | avg | 20ms | 30ms | 10ms | 50.03
| ProductNoticesStore.ClearOldNotices | avg | 13ms | 15ms | 2ms | 15.46
| PostStore.SearchPostsForUser | avg | 31ms | 34ms | 3ms | 9.73
| UserStore.GetAllProfilesInChannel | avg | 147ms | 153ms | 6ms | 4.08
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| EmojiStore.GetMultipleByName | p99 | 5ms | 24ms | 19ms | 383.71
| RoleStore.GetByNames | p99 | 5ms | 23ms | 18ms | 363.64
| JobStore.GetCountByStatusAndType | p99 | 9ms | 38ms | 29ms | 330.48
| ChannelStore.GetChannelUnread | p99 | 5ms | 21ms | 16ms | 323.23
| JobStore.GetNewestJobByStatusesAndType | p99 | 5ms | 18ms | 13ms | 262.63
| PostStore.GetPostReminderMetadata | p99 | 10ms | 23ms | 13ms | 135.40
| JobStore.Get | p99 | 8ms | 18ms | 10ms | 128.85
| PostStore.GetPostReminders | p99 | 10ms | 22ms | 12ms | 120.73
| PostStore.Update | p99 | 27ms | 58ms | 31ms | 114.84
| RoleStore.ChannelHigherScopedPermissions | p99 | 10ms | 20ms | 10ms | 104.90
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 10ms | 5ms | 101.00
| TeamStore.GetTotalMemberCount | p99 | 25ms | 50ms | 25ms | 100.60
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 9ms | 4ms | 80.81
| DraftStore.GetDraftsForUser | p99 | 10ms | 16ms | 6ms | 61.10
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 96ms | 152ms | 56ms | 58.32
| ChannelStore.GetAllChannelMembersForUser | p99 | 17ms | 24ms | 7ms | 41.31
| FileInfoStore.GetByIds | p99 | 7ms | 10ms | 3ms | 40.81
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 14ms | 19ms | 5ms | 35.65
| JobStore.GetAllByStatus | p99 | 15ms | 20ms | 5ms | 32.34
| DraftStore.Get | p99 | 6ms | 8ms | 2ms | 30.82
| ThreadStore.GetThreadsForUser | p99 | 10ms | 13ms | 3ms | 30.04
| PostStore.SearchPostsForUser | p99 | 592ms | 763ms | 171ms | 28.90
| UserStore.GetProfileByIds | p99 | 11ms | 14ms | 3ms | 27.16
| PostStore.GetPostIdAfterTime | p99 | 12ms | 15ms | 3ms | 25.37
| ThreadStore.GetTotalUnreadThreads | p99 | 12ms | 15ms | 3ms | 25.29
| DraftStore.Upsert | p99 | 14ms | 17ms | 3ms | 21.08
| GroupStore.GetGroups | p99 | 10ms | 12ms | 2ms | 20.20
| ChannelStore.Get | p99 | 11ms | 13ms | 2ms | 17.61
| ThreadStore.GetTotalThreads | p99 | 12ms | 14ms | 2ms | 17.28
| ChannelStore.IncrementMentionCount | p99 | 12ms | 14ms | 2ms | 16.94
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 12ms | 14ms | 2ms | 16.51
| SessionStore.Get | p99 | 25ms | 29ms | 4ms | 16.27
| SystemStore.GetByName | p99 | 13ms | 15ms | 2ms | 15.87
| ChannelStore.GetMemberLastViewedAt | p99 | 13ms | 15ms | 2ms | 14.93
| ChannelStore.GetMemberForPost | p99 | 13ms | 15ms | 2ms | 14.92
| ChannelStore.CreateInitialSidebarCategories | p99 | 62ms | 71ms | 9ms | 14.44
| TeamStore.SaveMember | p99 | 64ms | 73ms | 9ms | 14.00
| FileInfoStore.Save | p99 | 18ms | 20ms | 2ms | 10.82
| ChannelStore.SearchGroupChannels | p99 | 19ms | 21ms | 2ms | 10.55
| ChannelStore.GetGuestCount | p99 | 19ms | 21ms | 2ms | 10.28
| UserStore.Search | p99 | 57ms | 62ms | 5ms | 8.71
| ChannelStore.SaveMember | p99 | 84ms | 88ms | 4ms | 4.75
| ProductNoticesStore.View | p99 | 96ms | 99ms | 3ms | 3.12
| UserStore.Save | p99 | 197ms | 200ms | 3ms | 1.53
| ChannelStore.AutocompleteInTeamForSearch | p99 | 300ms | 303ms | 3ms | 1.00
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -107.01
| ChannelBookmarkStore.Delete | avg | 7ms | 0s | -7ms | -105.58
| FileInfoStore.DeleteForPost | avg | 6ms | 0s | -6ms | -98.30
| ChannelBookmarkStore.Get | avg | 2ms | 0s | -2ms | -90.94
| ChannelStore.AutocompleteInTeamForSearch | avg | 54ms | 36ms | -18ms | -33.61
| UserStore.Update | avg | 9ms | 7ms | -2ms | -21.90
| ChannelStore.GetTeamChannels | avg | 12ms | 10ms | -2ms | -16.62
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 18ms | 16ms | -2ms | -10.84
| StatusStore.SaveOrUpdate | avg | 21ms | 19ms | -2ms | -9.31
| ChannelStore.UpdateSidebarCategories | avg | 43ms | 40ms | -3ms | -6.96
| PostStore.AnalyticsPostCount | avg | 262ms | 258ms | -4ms | -1.53
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelBookmarkStore.Delete | p99 | 10ms | 0s | -10ms | -100.50
| FileInfoStore.DeleteForPost | p99 | 10ms | 0s | -10ms | -100.47
| UserStore.Update | p99 | 75ms | 22ms | -53ms | -71.14
| PostPersistentNotificationStore.Get | p99 | 21ms | 9ms | -12ms | -58.11
| PostPriorityStore.GetForPost | p99 | 20ms | 9ms | -11ms | -53.92
| PostAcknowledgementStore.GetForPost | p99 | 20ms | 9ms | -11ms | -53.92
| JobStore.Save | p99 | 38ms | 18ms | -20ms | -52.29
| StatusStore.UpdateExpiredDNDStatuses | p99 | 10ms | 5ms | -5ms | -52.22
| ChannelStore.GetPublicChannelsForTeam | p99 | 49ms | 25ms | -24ms | -48.60
| ChannelStore.UpdateSidebarCategories | p99 | 91ms | 50ms | -41ms | -45.06
| ChannelStore.GetPinnedPostCount | p99 | 9ms | 6ms | -3ms | -34.58
| UserStore.GetByUsername | p99 | 24ms | 16ms | -8ms | -33.40
| ChannelStore.Save | p99 | 44ms | 30ms | -14ms | -31.94
| PostPersistentNotificationStore.GetSingle | p99 | 7ms | 5ms | -2ms | -30.00
| ChannelStore.GetByName | p99 | 37ms | 31ms | -6ms | -16.32
| StatusStore.SaveOrUpdate | p99 | 388ms | 329ms | -59ms | -15.20
| FileInfoStore.AttachToPost | p99 | 23ms | 21ms | -2ms | -8.80
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 45ms | 43ms | -2ms | -4.44
| UserStore.AutocompleteUsersInChannel | p99 | 168ms | 162ms | -6ms | -3.57
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createDirectChannel | avg | 172ms | 191ms | 19ms | 11.04
| uploadFileStream | avg | 366ms | 374ms | 8ms | 2.18
| addTeamMember | avg | 585ms | 595ms | 10ms | 1.71
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelUnread | p99 | 5ms | 21ms | 16ms | 323.23
| followThreadByUser | p99 | 25ms | 48ms | 23ms | 92.56
| deletePost | p99 | 25ms | 48ms | 23ms | 92.56
| getDrafts | p99 | 10ms | 16ms | 6ms | 60.95
| patchPost | p99 | 54ms | 79ms | 25ms | 46.31
| searchPostsInTeam | p99 | 592ms | 763ms | 171ms | 28.90
| getTeamMember | p99 | 9ms | 11ms | 2ms | 23.01
| getChannel | p99 | 18ms | 21ms | 3ms | 16.39
| getClientConfig | p99 | 32ms | 36ms | 4ms | 12.36
| addTeamMember | p99 | 1.76s | 1.969s | 209ms | 11.88
| getPostsForChannelAroundLastUnread | p99 | 64ms | 71ms | 7ms | 10.93
| searchGroupChannels | p99 | 19ms | 21ms | 2ms | 10.55
| searchUsers | p99 | 62ms | 67ms | 5ms | 8.02
| viewChannel | p99 | 39ms | 41ms | 2ms | 5.10
| createDirectChannel | p99 | 472ms | 485ms | 13ms | 2.75
| autocompleteChannelsForTeamForSearch | p99 | 300ms | 303ms | 3ms | 1.00
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 4ms | 0s | -4ms | -92.72
| autocompleteChannelsForTeamForSearch | avg | 54ms | 36ms | -18ms | -33.57
| createChannel | avg | 232ms | 177ms | -55ms | -23.68
| createChannelBookmark | avg | 16ms | 14ms | -2ms | -12.16
| setPostReminder | avg | 20ms | 18ms | -2ms | -9.77
| getProfileImage | avg | 76ms | 71ms | -5ms | -6.62
| updateCategoriesForTeamForUser | avg | 64ms | 60ms | -4ms | -6.26
| removeUserCustomStatus | avg | 123ms | 118ms | -5ms | -4.08
| createGroupChannel | avg | 288ms | 282ms | -6ms | -2.09
| addChannelMember | avg | 183ms | 180ms | -3ms | -1.64
| createUser | avg | 125ms | 123ms | -2ms | -1.60
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 10ms | 0s | -10ms | -101.01
| createChannel | p99 | 494ms | 249ms | -245ms | -49.62
| setPostReminder | p99 | 49ms | 25ms | -24ms | -48.73
| getPublicChannelsForTeam | p99 | 49ms | 25ms | -24ms | -48.60
| saveReaction | p99 | 40ms | 32ms | -8ms | -20.09
| getProfileImage | p99 | 323ms | 260ms | -63ms | -19.49
| getChannelsForTeamForUser | p99 | 17ms | 15ms | -2ms | -11.70
| autocompleteUsers | p99 | 148ms | 136ms | -12ms | -8.08
| getChannelMember | p99 | 44ms | 42ms | -2ms | -4.55
| getCategoriesForTeamForUser | p99 | 45ms | 43ms | -2ms | -4.42
| getFilePreview | p99 | 98ms | 96ms | -2ms | -2.04
| addChannelMember | p99 | 468ms | 459ms | -9ms | -1.92
| createUser | p99 | 303ms | 298ms | -5ms | -1.65
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Delete |  Avg| 7ms| 0s | -7ms | -105.585
| |  P99| 10ms| 0s | -10ms | -100.503
| ChannelBookmarkStore.Get |  Avg| 2ms| 0s | -2ms | -90.938
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 19ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 33ms| 33ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 54ms| 36ms | -18ms | -33.611
| |  P99| 300ms| 303ms | 3ms | 1.000
| ChannelStore.CreateDirectChannel |  Avg| 22ms| 21ms | -1ms | -4.468
| |  P99| 50ms| 49ms | -1ms | -2.017
| ChannelStore.CreateInitialSidebarCategories |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 62ms| 71ms | 9ms | 14.435
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 17.607
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 24ms | 7ms | 41.310
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 16ms | -2ms | -10.841
| |  P99| 96ms| 152ms | 56ms | 58.324
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 37ms| 31ms | -6ms | -16.320
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 21ms | 16ms | 323.232
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.176
| ChannelStore.GetGuestCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.279
| ChannelStore.GetMember |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 45ms| 46ms | 1ms | 2.247
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 14.921
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 14.932
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -107.011
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 13ms | 1ms | 8.239
| ChannelStore.GetPinnedPostCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 6ms | -3ms | -34.582
| ChannelStore.GetPublicChannelsForTeam |  Avg| 13ms| 12ms | -1ms | -7.447
| |  P99| 49ms| 25ms | -24ms | -48.596
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 12ms| 11ms | -1ms | -8.173
| |  P99| 45ms| 43ms | -2ms | -4.441
| ChannelStore.GetSidebarCategory |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetTeamChannels |  Avg| 12ms| 10ms | -2ms | -16.618
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.938
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.Save |  Avg| 12ms| 11ms | -1ms | -8.664
| |  P99| 44ms| 30ms | -14ms | -31.940
| ChannelStore.SaveMember |  Avg| 27ms| 28ms | 1ms | 3.664
| |  P99| 84ms| 88ms | 4ms | 4.747
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 21ms | 2ms | 10.547
| ChannelStore.UpdateLastViewedAt |  Avg| 5ms| 4ms | -1ms | -21.972
| |  P99| 12ms| 13ms | 1ms | 8.080
| ChannelStore.UpdateSidebarCategories |  Avg| 43ms| 40ms | -3ms | -6.956
| |  P99| 91ms| 50ms | -41ms | -45.057
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 18.177
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 3ms | -1ms | -25.264
| |  P99| 10ms| 9ms | -1ms | -10.367
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 4ms| 3ms | -1ms | -26.867
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 30.825
| DraftStore.GetDraftsForUser |  Avg| 2ms| 3ms | 1ms | 40.409
| |  P99| 10ms| 16ms | 6ms | 61.104
| DraftStore.Upsert |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 17ms | 3ms | 21.079
| EmojiStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 2ms| 5ms | 3ms | 176.106
| |  P99| 5ms| 24ms | 19ms | 383.705
| FileInfoStore.AttachToPost |  Avg| 7ms| 6ms | -1ms | -14.064
| |  P99| 23ms| 21ms | -2ms | -8.796
| FileInfoStore.DeleteForPost |  Avg| 6ms| 0s | -6ms | -98.301
| |  P99| 10ms| 0s | -10ms | -100.468
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 17.055
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 10ms | 3ms | 40.815
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 10.821
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 22ms| 23ms | 1ms | 4.578
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.008
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.543
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.204
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 128.847
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 20ms | 5ms | 32.337
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 3ms | 1ms | 51.182
| |  P99| 9ms| 38ms | 29ms | 330.484
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.Save |  Avg| 5ms| 4ms | -1ms | -20.849
| |  P99| 38ms| 18ms | -20ms | -52.288
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.621
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 10.526
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 13ms | -1ms | -7.054
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 9ms | -11ms | -53.921
| PostAcknowledgementStore.GetForPosts |  Avg| 3ms| 2ms | -1ms | -39.993
| |  P99| 14ms| 14ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 21ms| 9ms | -12ms | -58.111
| PostPersistentNotificationStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.995
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 9ms | -11ms | -53.921
| PostPriorityStore.GetForPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 262ms| 258ms | -4ms | -1.528
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.331
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 25.369
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.147
| PostStore.GetPostReminderMetadata |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 135.398
| PostStore.GetPostReminders |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 120.733
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 15ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.714
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 13ms| 12ms | -1ms | -7.895
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 31ms| 34ms | 3ms | 9.735
| |  P99| 592ms| 763ms | 171ms | 28.903
| PostStore.SetPostReminder |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 15ms| 14ms | -1ms | -6.893
| |  P99| 27ms| 58ms | 31ms | 114.837
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 100.996
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 43ms| 43ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 13ms| 15ms | 2ms | 15.460
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 31ms| 32ms | 1ms | 3.198
| |  P99| 96ms| 99ms | 3ms | 3.116
| ReactionStore.GetForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 19ms| 18ms | -1ms | -5.142
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 4ms | 1ms | 29.451
| |  P99| 10ms| 20ms | 10ms | 104.895
| RoleStore.GetByNames |  Avg| 2ms| 3ms | 1ms | 56.000
| |  P99| 5ms| 23ms | 18ms | 363.636
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 25ms| 29ms | 4ms | 16.268
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.407
| SessionStore.GetSessionsExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 24ms| 25ms | 1ms | 4.098
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 16.051
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.723
| StatusStore.SaveOrUpdate |  Avg| 21ms| 19ms | -2ms | -9.311
| |  P99| 388ms| 329ms | -59ms | -15.203
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.219
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 3ms | -1ms | -27.959
| |  P99| 10ms| 10ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 15ms | 2ms | 15.870
| TeamStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.913
| TeamStore.GetActiveMemberCount |  Avg| 36ms| 35ms | -1ms | -2.801
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 3ms | 1ms | 42.686
| |  P99| 14ms| 19ms | 5ms | 35.645
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.314
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.226
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 20ms| 30ms | 10ms | 50.034
| |  P99| 25ms| 50ms | 25ms | 100.604
| TeamStore.SaveMember |  Avg| 24ms| 25ms | 1ms | 4.123
| |  P99| 64ms| 73ms | 9ms | 14.000
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.036
| ThreadStore.GetTeamsUnreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.920
| ThreadStore.GetThreadFollowers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.318
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.260
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.036
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 17.281
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.836
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 15ms | 3ms | 25.292
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.508
| ThreadStore.MaintainMembership |  Avg| 7ms| 6ms | -1ms | -15.290
| |  P99| 23ms| 22ms | -1ms | -4.389
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.309
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.152
| ThreadStore.UpdateMembership |  Avg| 4ms| 3ms | -1ms | -27.420
| |  P99| 10ms| 10ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 168ms| 162ms | -6ms | -3.572
| UserStore.Count |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 147ms| 153ms | 6ms | 4.076
| |  P99| 472ms| 474ms | 2ms | 0.424
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 24ms| 16ms | -8ms | -33.403
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 14ms | 3ms | 27.165
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.850
| UserStore.GetProfilesInChannel |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.505
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| UserStore.Save |  Avg| 73ms| 74ms | 1ms | 1.365
| |  P99| 197ms| 200ms | 3ms | 1.525
| UserStore.Search |  Avg| 14ms| 13ms | -1ms | -7.383
| |  P99| 57ms| 62ms | 5ms | 8.711
| UserStore.Update |  Avg| 9ms| 7ms | -2ms | -21.899
| |  P99| 75ms| 22ms | -53ms | -71.137
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.799
| UserStore.UpdateUpdateAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.839
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 32ms| 33ms | 1ms | 3.146
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 183ms| 180ms | -3ms | -1.638
| | P99| 468ms| 459ms | -9ms | -1.923
| addTeamMember | Avg| 585ms| 595ms | 10ms | 1.710
| | P99| 1.76s| 1.969s | 209ms | 11.875
| autocompleteChannelsForTeamForSearch | Avg| 54ms| 36ms | -18ms | -33.575
| | P99| 300ms| 303ms | 3ms | 1.000
| autocompleteUsers | Avg| 31ms| 30ms | -1ms | -3.176
| | P99| 148ms| 136ms | -12ms | -8.084
| createChannel | Avg| 232ms| 177ms | -55ms | -23.681
| | P99| 494ms| 249ms | -245ms | -49.620
| createChannelBookmark | Avg| 16ms| 14ms | -2ms | -12.158
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 172ms| 191ms | 19ms | 11.044
| | P99| 472ms| 485ms | 13ms | 2.754
| createGroupChannel | Avg| 288ms| 282ms | -6ms | -2.085
| | P99| 497ms| 496ms | -1ms | -0.201
| createPost | Avg| 178ms| 178ms | 0s | 0.000
| | P99| 770ms| 775ms | 5ms | 0.649
| createUser | Avg| 125ms| 123ms | -2ms | -1.605
| | P99| 303ms| 298ms | -5ms | -1.652
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| deletePost | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 25ms| 48ms | 23ms | 92.555
| followThreadByUser | Avg| 13ms| 14ms | 1ms | 7.790
| | P99| 25ms| 48ms | 23ms | 92.555
| getAllTeams | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| getCategoriesForTeamForUser | Avg| 12ms| 11ms | -1ms | -8.068
| | P99| 45ms| 43ms | -2ms | -4.419
| getChannel | Avg| 4ms| 5ms | 1ms | 22.518
| | P99| 18ms| 21ms | 3ms | 16.393
| getChannelMember | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 44ms| 42ms | -2ms | -4.551
| getChannelMembers | Avg| 4ms| 0s | -4ms | -92.716
| | P99| 10ms| 0s | -10ms | -101.011
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 16ms| 16ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 21ms | 16ms | 323.232
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 15ms | -2ms | -11.705
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getClientConfig | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 32ms| 36ms | 4ms | 12.364
| getDrafts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 16ms | 6ms | 60.954
| getFilePreview | Avg| 39ms| 38ms | -1ms | -2.552
| | P99| 98ms| 96ms | -2ms | -2.037
| getFileThumbnail | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 89ms| 90ms | 1ms | 1.120
| getPostThread | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 26ms | 1ms | 4.008
| getPostsForChannel | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 167ms| 166ms | -1ms | -0.600
| getPostsForChannelAroundLastUnread | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 64ms| 71ms | 7ms | 10.925
| getPreferences | Avg| 4ms| 3ms | -1ms | -28.315
| | P99| 22ms| 23ms | 1ms | 4.484
| getProfileImage | Avg| 76ms| 71ms | -5ms | -6.618
| | P99| 323ms| 260ms | -63ms | -19.495
| getPublicChannelsForTeam | Avg| 14ms| 13ms | -1ms | -6.937
| | P99| 49ms| 25ms | -24ms | -48.596
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 11ms | 2ms | 23.014
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.652
| getTeamStats | Avg| 36ms| 35ms | -1ms | -2.795
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 16ms| 17ms | 1ms | 6.226
| getTeamsUnreadForUser | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 15ms| 16ms | 1ms | 6.788
| getUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 22ms | 1ms | 4.698
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| login | Avg| 63ms| 64ms | 1ms | 1.576
| | P99| 247ms| 247ms | 0s | 0.000
| logout | Avg| 26ms| 25ms | -1ms | -3.907
| | P99| 50ms| 49ms | -1ms | -2.015
| patchPost | Avg| 27ms| 26ms | -1ms | -3.652
| | P99| 54ms| 79ms | 25ms | 46.305
| removeUserCustomStatus | Avg| 123ms| 118ms | -5ms | -4.081
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 40ms| 32ms | -8ms | -20.092
| searchAllChannels | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 21ms | 2ms | 10.547
| searchPostsInTeam | Avg| 40ms| 41ms | 1ms | 2.523
| | P99| 592ms| 763ms | 171ms | 28.903
| searchUsers | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 62ms| 67ms | 5ms | 8.016
| setPostReminder | Avg| 20ms| 18ms | -2ms | -9.768
| | P99| 49ms| 25ms | -24ms | -48.731
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 64ms| 60ms | -4ms | -6.263
| | P99| 100ms| 100ms | 0s | 0.000
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 94ms| 94ms | 0s | 0.000
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 366ms| 374ms | 8ms | 2.184
| | P99| 983ms| 984ms | 1ms | 0.102
| upsertDraft | Avg| 5ms| 4ms | -1ms | -21.850
| | P99| 18ms| 19ms | 1ms | 5.526
| viewChannel | Avg| 12ms| 11ms | -1ms | -8.428
| | P99| 39ms| 41ms | 2ms | 5.100

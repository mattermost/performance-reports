### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.Count | avg | 9ms | 11ms | 2ms | 21.55
| ChannelStore.AutocompleteInTeamForSearch | avg | 21ms | 25ms | 4ms | 18.63
| PostStore.Delete | avg | 12ms | 14ms | 2ms | 16.01
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetSidebarCategory | p99 | 24ms | 75ms | 51ms | 216.63
| JobStore.UpdateStatusOptimistically | p99 | 5ms | 14ms | 9ms | 181.82
| LinkMetadataStore.Save | p99 | 8ms | 20ms | 12ms | 147.31
| ClusterDiscoveryStore.SetLastPingAt | p99 | 10ms | 23ms | 13ms | 132.65
| PostStore.SetPostReminder | p99 | 10ms | 23ms | 13ms | 130.65
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 23ms | 46ms | 23ms | 101.77
| PreferenceStore.DeleteCategoryAndName | p99 | 5ms | 10ms | 5ms | 101.01
| UserStore.Count | p99 | 23ms | 45ms | 22ms | 94.31
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 5ms | 9ms | 4ms | 80.81
| StatusStore.UpdateExpiredDNDStatuses | p99 | 13ms | 22ms | 9ms | 70.45
| ChannelStore.CreateDirectChannel | p99 | 25ms | 38ms | 13ms | 52.06
| JobStore.GetAllByStatus | p99 | 6ms | 9ms | 3ms | 49.18
| JobStore.UpdateOptimistically | p99 | 6ms | 8ms | 2ms | 34.78
| PostStore.GetPosts | p99 | 10ms | 12ms | 2ms | 20.20
| UserStore.Update | p99 | 10ms | 12ms | 2ms | 20.01
| ChannelStore.AutocompleteInTeamForSearch | p99 | 79ms | 94ms | 15ms | 18.94
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 29ms | 4ms | 16.00
| ChannelStore.Save | p99 | 34ms | 39ms | 5ms | 14.93
| UserStore.AutocompleteUsersInChannel | p99 | 157ms | 163ms | 6ms | 3.81
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | avg | 2ms | 0s | -2ms | -131.11
| PostPersistentNotificationStore.UpdateLastActivity | avg | 3ms | 0s | -3ms | -97.59
| PostStore.AnalyticsPostCount | avg | 262ms | 132ms | -130ms | -49.62
| UserStore.GetProfilesInChannel | avg | 38ms | 30ms | -8ms | -20.90
| StatusStore.SaveOrUpdate | avg | 15ms | 12ms | -3ms | -19.50
| ChannelStore.UpdateSidebarCategories | avg | 35ms | 32ms | -3ms | -8.63
| PostStore.SearchPostsForUser | avg | 105ms | 98ms | -7ms | -6.69
| UserStore.GetAllProfilesInChannel | avg | 140ms | 134ms | -6ms | -4.30
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| RoleStore.GetByNames | p99 | 17ms | 5ms | -12ms | -72.29
| PostPersistentNotificationStore.DeleteExpired | p99 | 17ms | 5ms | -12ms | -70.38
| JobStore.UpdateStatus | p99 | 12ms | 5ms | -7ms | -57.14
| PostStore.GetPostReminders | p99 | 23ms | 10ms | -13ms | -55.56
| PostPersistentNotificationStore.Get | p99 | 9ms | 5ms | -4ms | -46.78
| SessionStore.Remove | p99 | 9ms | 5ms | -4ms | -46.24
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -42.25
| StatusStore.SaveOrUpdate | p99 | 362ms | 218ms | -144ms | -39.82
| JobStore.GetCountByStatusAndType | p99 | 18ms | 12ms | -6ms | -32.48
| StatusStore.GetByIds | p99 | 7ms | 5ms | -2ms | -30.65
| RoleStore.ChannelHigherScopedPermissions | p99 | 7ms | 5ms | -2ms | -29.60
| PluginStore.List | p99 | 7ms | 5ms | -2ms | -29.41
| FileInfoStore.AttachToPost | p99 | 14ms | 10ms | -4ms | -28.35
| UserStore.UpdateFailedPasswordAttempts | p99 | 15ms | 11ms | -4ms | -26.53
| DraftStore.Delete | p99 | 9ms | 7ms | -2ms | -22.96
| PluginStore.SetWithOptions | p99 | 14ms | 12ms | -2ms | -14.00
| UserStore.GetAllProfilesInChannel | p99 | 436ms | 381ms | -55ms | -12.62
| PostStore.SearchPostsForUser | p99 | 1.098s | 960ms | -138ms | -12.57
| ChannelStore.SearchGroupChannels | p99 | 19ms | 17ms | -2ms | -10.60
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 90ms | 81ms | -9ms | -10.01
| ChannelStore.GetByName | p99 | 20ms | 18ms | -2ms | -9.81
| WebhookStore.GetOutgoingByTeam | p99 | 25ms | 23ms | -2ms | -8.04
| ChannelStore.SaveMember | p99 | 51ms | 49ms | -2ms | -3.91
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | avg | 15ms | 19ms | 4ms | 25.91
| deletePost | avg | 17ms | 20ms | 3ms | 17.57
| autocompleteChannelsForTeamForSearch | avg | 22ms | 25ms | 3ms | 13.94
| createUser | avg | 127ms | 139ms | 12ms | 9.45
| createChannel | avg | 167ms | 181ms | 14ms | 8.37
| createCategoryForTeamForUser | avg | 25ms | 27ms | 2ms | 7.94
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 25ms | 93ms | 68ms | 273.64
| updateCategoriesForTeamForUser | p99 | 98ms | 211ms | 113ms | 114.77
| deletePost | p99 | 25ms | 48ms | 23ms | 92.56
| autocompleteChannelsForTeamForSearch | p99 | 79ms | 94ms | 15ms | 18.94
| getPublicChannelsForTeam | p99 | 25ms | 29ms | 4ms | 16.00
| updateReadStateThreadByUser | p99 | 55ms | 60ms | 5ms | 9.17
| autocompleteUsers | p99 | 118ms | 128ms | 10ms | 8.50
| createUser | p99 | 398ms | 415ms | 17ms | 4.27
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createEmoji | avg | 6ms | 0s | -6ms | -100.34
| getRolesByNames | avg | 4ms | 1ms | -3ms | -73.44
| getProfileImage | avg | 97ms | 86ms | -11ms | -11.37
| createGroupChannel | avg | 256ms | 228ms | -28ms | -10.93
| createDirectChannel | avg | 169ms | 158ms | -11ms | -6.50
| searchPostsInTeam | avg | 110ms | 103ms | -7ms | -6.38
| addChannelMember | avg | 160ms | 152ms | -8ms | -5.00
| uploadFileStream | avg | 453ms | 434ms | -19ms | -4.19
| removeUserCustomStatus | avg | 107ms | 103ms | -4ms | -3.74
| login | avg | 62ms | 60ms | -2ms | -3.23
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| listCPAFields | p99 | 5ms | 0s | -5ms | -101.01
| createEmoji | p99 | 10ms | 0s | -10ms | -100.50
| createSchedulePost | p99 | 21ms | 9ms | -12ms | -57.66
| unfollowThreadByUser | p99 | 48ms | 25ms | -23ms | -47.92
| logout | p99 | 87ms | 49ms | -38ms | -43.93
| getChannel | p99 | 18ms | 11ms | -7ms | -38.15
| getDrafts | p99 | 7ms | 5ms | -2ms | -28.55
| searchPostsInTeam | p99 | 1.098s | 961ms | -137ms | -12.48
| getChannelMember | p99 | 19ms | 17ms | -2ms | -10.63
| patchPost | p99 | 48ms | 44ms | -4ms | -8.29
| getProfileImage | p99 | 473ms | 440ms | -33ms | -6.98
| getPostsForChannel | p99 | 96ms | 91ms | -5ms | -5.18
| createDirectChannel | p99 | 477ms | 465ms | -12ms | -2.52
| addChannelMember | p99 | 416ms | 406ms | -10ms | -2.41
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -42.254
| ChannelBookmarkStore.Delete |  Avg| 6ms| 5ms | -1ms | -15.853
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelBookmarkStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 9ms| 8ms | -1ms | -11.582
| |  P99| 25ms| 24ms | -1ms | -4.080
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 21ms| 25ms | 4ms | 18.632
| |  P99| 79ms| 94ms | 15ms | 18.940
| ChannelStore.CreateDirectChannel |  Avg| 16ms| 17ms | 1ms | 6.063
| |  P99| 25ms| 38ms | 13ms | 52.060
| ChannelStore.CreateInitialSidebarCategories |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 45ms| 44ms | -1ms | -2.206
| ChannelStore.CreateSidebarCategory |  Avg| 24ms| 23ms | -1ms | -4.229
| |  P99| 49ms| 50ms | 1ms | 2.062
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 18.650
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 17ms | -1ms | -5.516
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 11ms | -1ms | -8.481
| |  P99| 90ms| 81ms | -9ms | -10.011
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 20ms| 18ms | -2ms | -9.805
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -18.003
| ChannelStore.GetChannelsByIds |  Avg| 1ms| 0s | -1ms | -79.406
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 34ms| 34ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 29ms | 4ms | 16.001
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 11ms| 10ms | -1ms | -9.436
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.GetSidebarCategory |  Avg| 6ms| 7ms | 1ms | 16.947
| |  P99| 24ms| 75ms | 51ms | 216.626
| ChannelStore.GetTeamChannels |  Avg| 11ms| 10ms | -1ms | -9.378
| |  P99| 25ms| 24ms | -1ms | -4.053
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 34ms| 39ms | 5ms | 14.925
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 51ms| 49ms | -2ms | -3.908
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 17ms | -2ms | -10.596
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 35ms| 32ms | -3ms | -8.626
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 2ms | 1ms | 67.735
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 132.653
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 0s | -2ms | -131.111
| |  P99| 5ms| 0s | -5ms | -101.010
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.959
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 5ms| 6ms | 1ms | 20.555
| |  P99| 23ms| 46ms | 23ms | 101.769
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -28.353
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 22ms | 1ms | 4.654
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 1ms | -1ms | -65.005
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 9ms | 3ms | 49.180
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 1ms | -1ms | -57.543
| |  P99| 18ms| 12ms | -6ms | -32.476
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 34.783
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 5ms | -7ms | -57.143
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 4ms | 1ms | 30.266
| |  P99| 5ms| 14ms | 9ms | 181.818
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 3ms| 4ms | 1ms | 34.130
| |  P99| 8ms| 20ms | 12ms | 147.315
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PluginStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.412
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.001
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 1ms | -1ms | -56.291
| |  P99| 17ms| 5ms | -12ms | -70.381
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.784
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 3ms| 0s | -3ms | -97.587
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 262ms| 132ms | -130ms | -49.619
| |  P99| 498ms| 495ms | -3ms | -0.603
| PostStore.AnalyticsPostCountByTeam |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Delete |  Avg| 12ms| 14ms | 2ms | 16.008
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 22ms| 22ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.678
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 3ms | 1ms | 44.161
| |  P99| 21ms| 21ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 23ms| 10ms | -13ms | -55.556
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.199
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostsByIds |  Avg| 1ms| 0s | -1ms | -73.537
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 6ms| 7ms | 1ms | 15.392
| |  P99| 41ms| 41ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 39ms| 39ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 105ms| 98ms | -7ms | -6.687
| |  P99| 1.098s| 960ms | -138ms | -12.574
| PostStore.SetPostReminder |  Avg| 6ms| 7ms | 1ms | 16.331
| |  P99| 10ms| 23ms | 13ms | 130.653
| PostStore.Update |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 3ms | 1ms | 54.233
| |  P99| 5ms| 10ms | 5ms | 101.010
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.388
| PreferenceStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.GetViews |  Avg| 2ms| 1ms | -1ms | -58.597
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 27ms| 26ms | -1ms | -3.646
| |  P99| 93ms| 92ms | -1ms | -1.081
| PropertyFieldStore.SearchPropertyFields |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 2ms| 3ms | 1ms | 42.809
| |  P99| 9ms| 9ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -29.595
| RoleStore.GetByNames |  Avg| 2ms| 1ms | -1ms | -63.697
| |  P99| 17ms| 5ms | -12ms | -72.289
| ScheduledPostStore.CreateScheduledPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 1ms| 2ms | 1ms | 66.779
| |  P99| 8ms| 9ms | 1ms | 11.905
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| SessionStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 18ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 1ms | -1ms | -66.188
| |  P99| 9ms| 9ms | 0s | 0.000
| SessionStore.Remove |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -46.243
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.665
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -30.648
| StatusStore.SaveOrUpdate |  Avg| 15ms| 12ms | -3ms | -19.495
| |  P99| 362ms| 218ms | -144ms | -39.823
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 2ms| 3ms | 1ms | 43.511
| |  P99| 13ms| 22ms | 9ms | 70.450
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetMany |  Avg| 1ms| 0s | -1ms | -91.044
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.258
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.914
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.415
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 2ms | 1ms | 71.556
| |  P99| 9ms| 10ms | 1ms | 11.170
| UserStore.AnalyticsActiveCount |  Avg| 13ms| 14ms | 1ms | 7.627
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 35ms| 35ms | 0s | 0.000
| |  P99| 157ms| 163ms | 6ms | 3.812
| UserStore.Count |  Avg| 9ms| 11ms | 2ms | 21.553
| |  P99| 23ms| 45ms | 22ms | 94.312
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.948
| UserStore.GetAllProfilesInChannel |  Avg| 140ms| 134ms | -6ms | -4.295
| |  P99| 436ms| 381ms | -55ms | -12.621
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -14.066
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 38ms| 30ms | -8ms | -20.900
| |  P99| 244ms| 243ms | -1ms | -0.409
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.408
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 20.007
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 11ms | -4ms | -26.530
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.005
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 25ms| 23ms | -2ms | -8.044
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 160ms| 152ms | -8ms | -5.005
| | P99| 416ms| 406ms | -10ms | -2.405
| addTeamMember | Avg| 477ms| 474ms | -3ms | -0.629
| | P99| 987ms| 987ms | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 22ms| 25ms | 3ms | 13.938
| | P99| 79ms| 94ms | 15ms | 18.940
| autocompleteUsers | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 118ms| 128ms | 10ms | 8.500
| createCategoryForTeamForUser | Avg| 25ms| 27ms | 2ms | 7.942
| | P99| 50ms| 50ms | 0s | 0.000
| createChannel | Avg| 167ms| 181ms | 14ms | 8.368
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 15ms| 14ms | -1ms | -6.880
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 169ms| 158ms | -11ms | -6.504
| | P99| 477ms| 465ms | -12ms | -2.517
| createEmoji | Avg| 6ms| 0s | -6ms | -100.345
| | P99| 10ms| 0s | -10ms | -100.503
| createGroupChannel | Avg| 256ms| 228ms | -28ms | -10.928
| | P99| 495ms| 494ms | -1ms | -0.202
| createPost | Avg| 165ms| 165ms | 0s | 0.000
| | P99| 492ms| 491ms | -1ms | -0.203
| createSchedulePost | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 9ms | -12ms | -57.662
| createUser | Avg| 127ms| 139ms | 12ms | 9.451
| | P99| 398ms| 415ms | 17ms | 4.268
| deleteDraft | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -15.912
| deletePost | Avg| 17ms| 20ms | 3ms | 17.575
| | P99| 25ms| 48ms | 23ms | 92.555
| followThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 8ms | -1ms | -11.700
| getCategoriesForTeamForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 25ms| 26ms | 1ms | 3.977
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 11ms | -7ms | -38.147
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 19ms| 17ms | -2ms | -10.634
| getChannelMembers | Avg| 4ms| 3ms | -1ms | -28.131
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getChannelMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getChannelUnread | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 6ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| getClientConfig | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 5ms | -2ms | -28.553
| getFilePreview | Avg| 37ms| 37ms | 0s | 0.000
| | P99| 94ms| 93ms | -1ms | -1.063
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 87ms| 86ms | -1ms | -1.145
| getPostThread | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getPostsForChannel | Avg| 15ms| 14ms | -1ms | -6.720
| | P99| 96ms| 91ms | -5ms | -5.183
| getPostsForChannelAroundLastUnread | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 39ms| 40ms | 1ms | 2.539
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 9ms | 1ms | 12.300
| getProfileImage | Avg| 97ms| 86ms | -11ms | -11.373
| | P99| 473ms| 440ms | -33ms | -6.979
| getPublicChannelsForTeam | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 29ms | 4ms | 16.001
| getRolesByNames | Avg| 4ms| 1ms | -3ms | -73.440
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getTeamScheduledPosts | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getTeamStats | Avg| 35ms| 35ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 12ms| 13ms | 1ms | 8.260
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 1ms| 0s | -1ms | -71.704
| | P99| 5ms| 0s | -5ms | -101.010
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 62ms| 60ms | -2ms | -3.231
| | P99| 234ms| 234ms | 0s | 0.000
| logout | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 87ms| 49ms | -38ms | -43.930
| patchPost | Avg| 21ms| 20ms | -1ms | -4.819
| | P99| 48ms| 44ms | -4ms | -8.293
| removeUserCustomStatus | Avg| 107ms| 103ms | -4ms | -3.739
| | P99| 247ms| 247ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| searchAllChannels | Avg| 32ms| 33ms | 1ms | 3.086
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 18ms | -1ms | -5.232
| searchPostsInTeam | Avg| 110ms| 103ms | -7ms | -6.378
| | P99| 1.098s| 961ms | -137ms | -12.483
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| setPostReminder | Avg| 15ms| 19ms | 4ms | 25.912
| | P99| 25ms| 93ms | 68ms | 273.642
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 48ms| 25ms | -23ms | -47.917
| updateCategoriesForTeamForUser | Avg| 48ms| 48ms | 0s | 0.000
| | P99| 98ms| 211ms | 113ms | 114.773
| updateChannelBookmark | Avg| 18ms| 18ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updatePreferences | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 28ms| 29ms | 1ms | 3.572
| | P99| 55ms| 60ms | 5ms | 9.169
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 453ms| 434ms | -19ms | -4.194
| | P99| 993ms| 990ms | -3ms | -0.302
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000

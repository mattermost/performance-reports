### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | avg | 2ms | 13ms | 11ms | 466.94
| ScheduledPostStore.GetPendingScheduledPosts | avg | 2ms | 4ms | 2ms | 117.59
| PostStore.GetPostReminderMetadata | avg | 2ms | 4ms | 2ms | 96.16
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 3ms | 5ms | 2ms | 70.85
| UserStore.Update | avg | 5ms | 7ms | 2ms | 41.49
| PostStore.Update | avg | 9ms | 11ms | 2ms | 22.40
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 12ms | 14ms | 2ms | 16.24
| UserStore.GetAllProfilesInChannel | avg | 134ms | 140ms | 6ms | 4.46
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| StatusStore.SaveOrUpdate | p99 | 9ms | 234ms | 225ms | 2583.84
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 5ms | 46ms | 41ms | 828.28
| PostStore.GetPostReminderMetadata | p99 | 5ms | 24ms | 19ms | 383.80
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 10ms | 47ms | 37ms | 381.51
| PostStore.Update | p99 | 24ms | 113ms | 89ms | 366.30
| UserStore.Update | p99 | 17ms | 75ms | 58ms | 337.24
| PluginStore.List | p99 | 5ms | 20ms | 15ms | 303.03
| JobStore.GetAllByStatus | p99 | 9ms | 20ms | 11ms | 120.31
| ChannelStore.CreateDirectChannel | p99 | 32ms | 67ms | 35ms | 108.11
| SessionStore.GetSessionsExpired | p99 | 5ms | 10ms | 5ms | 101.01
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.GetChannelUnread | p99 | 5ms | 9ms | 4ms | 80.81
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 9ms | 4ms | 80.81
| ChannelStore.GetSidebarCategory | p99 | 24ms | 41ms | 17ms | 69.89
| JobStore.UpdateStatus | p99 | 5ms | 8ms | 3ms | 60.61
| StatusStore.UpdateLastActivityAt | p99 | 5ms | 8ms | 3ms | 58.89
| ChannelStore.GetPublicChannelsForTeam | p99 | 25ms | 39ms | 14ms | 56.00
| ChannelStore.GetAllChannelMembersForUser | p99 | 14ms | 21ms | 7ms | 50.36
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 89ms | 127ms | 38ms | 42.52
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 10ms | 14ms | 4ms | 40.43
| FileInfoStore.GetByIds | p99 | 5ms | 7ms | 2ms | 40.24
| DraftStore.Delete | p99 | 5ms | 7ms | 2ms | 40.12
| ChannelStore.GetPinnedPostCount | p99 | 5ms | 7ms | 2ms | 40.03
| PostAcknowledgementStore.GetForPost | p99 | 9ms | 12ms | 3ms | 32.30
| SessionStore.GetLRUSessions | p99 | 10ms | 13ms | 3ms | 30.97
| UserTermsOfServiceStore.GetByUser | p99 | 10ms | 13ms | 3ms | 30.27
| UserStore.GetProfileByIds | p99 | 8ms | 10ms | 2ms | 24.49
| PreferenceStore.Save | p99 | 25ms | 31ms | 6ms | 24.24
| ThreadStore.GetTotalUnreadThreads | p99 | 10ms | 12ms | 2ms | 19.73
| UserStore.GetUnreadCount | p99 | 11ms | 13ms | 2ms | 18.16
| TeamStore.GetAllPage | p99 | 12ms | 14ms | 2ms | 17.16
| TeamStore.GetTeamsForUser | p99 | 15ms | 17ms | 2ms | 13.63
| ChannelStore.SaveMember | p99 | 67ms | 76ms | 9ms | 13.46
| UserStore.UpdateLastLogin | p99 | 15ms | 17ms | 2ms | 13.41
| UserStore.AutocompleteUsersInChannel | p99 | 163ms | 183ms | 20ms | 12.29
| ChannelStore.SearchGroupChannels | p99 | 18ms | 20ms | 2ms | 11.39
| SessionStore.Get | p99 | 22ms | 24ms | 2ms | 9.18
| ChannelStore.CreateInitialSidebarCategories | p99 | 44ms | 47ms | 3ms | 6.83
| ChannelStore.Save | p99 | 35ms | 37ms | 2ms | 5.80
| UserStore.GetAllProfilesInChannel | p99 | 445ms | 454ms | 9ms | 2.02
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | avg | 3ms | 0s | -3ms | -119.09
| EmojiStore.GetMultipleByName | avg | 3ms | 1ms | -2ms | -62.45
| ChannelStore.AutocompleteInTeamForSearch | avg | 28ms | 18ms | -10ms | -35.78
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 12ms | 10ms | -2ms | -16.75
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetMembers | p99 | 5ms | 0s | -5ms | -101.01
| JobStore.Save | p99 | 38ms | 5ms | -33ms | -86.27
| ChannelStore.GetChannelsByUser | p99 | 20ms | 5ms | -15ms | -76.52
| JobStore.UpdateOptimistically | p99 | 18ms | 8ms | -10ms | -55.71
| BotStore.Get | p99 | 10ms | 5ms | -5ms | -52.22
| PostStore.GetPostReminders | p99 | 9ms | 5ms | -4ms | -43.72
| JobStore.Get | p99 | 9ms | 5ms | -4ms | -43.40
| FileInfoStore.SetContent | p99 | 24ms | 14ms | -10ms | -42.46
| FileInfoStore.AttachToPost | p99 | 17ms | 10ms | -7ms | -41.05
| ThreadStore.MarkAllAsReadByChannels | p99 | 8ms | 5ms | -3ms | -36.15
| LinkMetadataStore.Save | p99 | 8ms | 5ms | -3ms | -35.72
| UserStore.GetByUsername | p99 | 8ms | 5ms | -3ms | -35.50
| FileInfoStore.Save | p99 | 14ms | 10ms | -4ms | -27.97
| ThreadStore.Get | p99 | 7ms | 5ms | -2ms | -27.78
| ChannelStore.GetMember | p99 | 16ms | 12ms | -4ms | -25.49
| ClusterDiscoveryStore.SetLastPingAt | p99 | 16ms | 12ms | -4ms | -24.85
| ChannelStore.AutocompleteInTeamForSearch | p99 | 94ms | 71ms | -23ms | -24.45
| TeamStore.GetTeamsByUserId | p99 | 14ms | 11ms | -3ms | -21.92
| ThreadStore.GetTotalUnreadMentions | p99 | 13ms | 11ms | -2ms | -15.49
| ChannelStore.GetMemberForPost | p99 | 13ms | 11ms | -2ms | -15.32
| ChannelStore.GetByName | p99 | 33ms | 31ms | -2ms | -6.01
| UserStore.Save | p99 | 139ms | 134ms | -5ms | -3.61
| PostStore.SearchPostsForUser | p99 | 496ms | 490ms | -6ms | -1.21
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createChannel | avg | 141ms | 198ms | 57ms | 40.41
| setPostReminder | avg | 14ms | 16ms | 2ms | 14.65
| patchPost | avg | 19ms | 21ms | 2ms | 10.70
| createDirectChannel | avg | 144ms | 153ms | 9ms | 6.27
| removeUserCustomStatus | avg | 105ms | 111ms | 6ms | 5.74
| updateCategoriesForTeamForUser | avg | 41ms | 43ms | 2ms | 4.87
| getProfileImage | avg | 69ms | 72ms | 3ms | 4.32
| uploadFileStream | avg | 386ms | 400ms | 14ms | 3.63
| createPost | avg | 152ms | 157ms | 5ms | 3.28
| addTeamMember | avg | 505ms | 520ms | 15ms | 2.97
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannel | p99 | 9ms | 44ms | 35ms | 382.49
| patchPost | p99 | 25ms | 113ms | 88ms | 354.04
| setPostReminder | p99 | 25ms | 49ms | 24ms | 96.58
| getChannelUnread | p99 | 5ms | 9ms | 4ms | 80.81
| createDirectChannel | p99 | 249ms | 448ms | 199ms | 79.76
| getPublicChannelsForTeam | p99 | 25ms | 39ms | 14ms | 56.00
| autocompleteUsers | p99 | 136ms | 164ms | 28ms | 20.62
| getProfileImage | p99 | 290ms | 342ms | 52ms | 17.90
| searchGroupChannels | p99 | 18ms | 20ms | 2ms | 11.20
| createPost | p99 | 497ms | 517ms | 20ms | 4.02
| searchUsers | p99 | 50ms | 52ms | 2ms | 4.01
| updateCategoriesForTeamForUser | p99 | 96ms | 98ms | 2ms | 2.09
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 3ms | 0s | -3ms | -104.76
| autocompleteChannelsForTeamForSearch | avg | 28ms | 18ms | -10ms | -35.70
| createChannelBookmark | avg | 12ms | 10ms | -2ms | -16.76
| getCategoriesForTeamForUser | avg | 12ms | 10ms | -2ms | -16.56
| createGroupChannel | avg | 246ms | 229ms | -17ms | -6.92
| addChannelMember | avg | 159ms | 150ms | -9ms | -5.65
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| updateUserCustomStatus | p99 | 33ms | 5ms | -28ms | -84.84
| getChannelsForUser | p99 | 20ms | 5ms | -15ms | -76.52
| followThreadByUser | p99 | 24ms | 10ms | -14ms | -57.91
| autocompleteChannelsForTeamForSearch | p99 | 94ms | 71ms | -23ms | -24.45
| getTeamsForUser | p99 | 14ms | 11ms | -3ms | -21.67
| addChannelMember | p99 | 433ms | 406ms | -27ms | -6.23
| getPostsForChannel | p99 | 108ms | 103ms | -5ms | -4.63
| getFilePreview | p99 | 99ms | 97ms | -2ms | -2.02
| searchPostsInTeam | p99 | 496ms | 490ms | -6ms | -1.21
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.165
| BotStore.Get |  Avg| 3ms| 2ms | -1ms | -36.840
| |  P99| 10ms| 5ms | -5ms | -52.219
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelBookmarkStore.Save |  Avg| 6ms| 7ms | 1ms | 17.323
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 11ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 32ms| 33ms | 1ms | 3.078
| |  P99| 98ms| 98ms | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 28ms| 18ms | -10ms | -35.778
| |  P99| 94ms| 71ms | -23ms | -24.449
| ChannelStore.CreateDirectChannel |  Avg| 14ms| 15ms | 1ms | 7.046
| |  P99| 32ms| 67ms | 35ms | 108.109
| ChannelStore.CreateInitialSidebarCategories |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 44ms| 47ms | 3ms | 6.830
| ChannelStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.049
| ChannelStore.GetAllChannelMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 21ms | 7ms | 50.365
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 12ms| 14ms | 2ms | 16.240
| |  P99| 89ms| 127ms | 38ms | 42.517
| ChannelStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 33ms| 31ms | -2ms | -6.014
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 5ms | -15ms | -76.523
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.975
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.367
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.742
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 12ms | -4ms | -25.493
| ChannelStore.GetMemberCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| ChannelStore.GetMemberForPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.317
| ChannelStore.GetMemberLastViewedAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.079
| ChannelStore.GetMembers |  Avg| 3ms| 0s | -3ms | -119.094
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetMembersForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.159
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 2ms | 1ms | 67.350
| |  P99| 5ms| 7ms | 2ms | 40.025
| ChannelStore.GetPublicChannelsForTeam |  Avg| 12ms| 13ms | 1ms | 8.109
| |  P99| 25ms| 39ms | 14ms | 56.003
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 12ms| 10ms | -2ms | -16.751
| |  P99| 40ms| 39ms | -1ms | -2.494
| ChannelStore.GetSidebarCategory |  Avg| 7ms| 8ms | 1ms | 15.079
| |  P99| 24ms| 41ms | 17ms | 69.887
| ChannelStore.GetTeamChannels |  Avg| 11ms| 12ms | 1ms | 9.199
| |  P99| 25ms| 25ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelStore.IsReadOnlyChannel |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 7ms | 1ms | 15.507
| ChannelStore.Save |  Avg| 8ms| 9ms | 1ms | 12.417
| |  P99| 35ms| 37ms | 2ms | 5.797
| ChannelStore.SaveMember |  Avg| 22ms| 23ms | 1ms | 4.503
| |  P99| 67ms| 76ms | 9ms | 13.464
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 20ms | 2ms | 11.388
| ChannelStore.UpdateLastViewedAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.853
| ChannelStore.UpdateSidebarCategories |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.020
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 12ms | -4ms | -24.846
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.124
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 3ms| 5ms | 2ms | 70.853
| |  P99| 10ms| 47ms | 37ms | 381.509
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 3ms| 1ms | -2ms | -62.450
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 10ms | -7ms | -41.054
| FileInfoStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 7ms | 2ms | 40.236
| FileInfoStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 10ms | -4ms | -27.973
| FileInfoStore.SetContent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 14ms | -10ms | -42.462
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| GroupStore.GetGroups |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.400
| JobStore.GetAllByStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 20ms | 11ms | 120.312
| JobStore.GetCountByStatusAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 3ms| 2ms | -1ms | -33.621
| |  P99| 38ms| 5ms | -33ms | -86.275
| JobStore.UpdateOptimistically |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 18ms| 8ms | -10ms | -55.710
| JobStore.UpdateStatus |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateStatusOptimistically |  Avg| 2ms| 3ms | 1ms | 40.045
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 18.622
| LinkMetadataStore.Save |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.716
| PluginStore.Delete |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 20ms | 15ms | 303.030
| PluginStore.SetWithOptions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.213
| PostAcknowledgementStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 12ms | 3ms | 32.300
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 261ms| 262ms | 1ms | 0.383
| |  P99| 498ms| 498ms | 0s | 0.000
| PostStore.Delete |  Avg| 9ms| 10ms | 1ms | 11.358
| |  P99| 24ms| 25ms | 1ms | 4.162
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.548
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 8.915
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.785
| PostStore.GetPostIdBeforeTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 2ms| 4ms | 2ms | 96.162
| |  P99| 5ms| 24ms | 19ms | 383.795
| PostStore.GetPostReminders |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.716
| PostStore.GetPosts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.556
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.661
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 44ms| 44ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 7ms| 8ms | 1ms | 13.440
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 23ms| 23ms | 0s | 0.000
| |  P99| 496ms| 490ms | -6ms | -1.209
| PostStore.SetPostReminder |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Update |  Avg| 9ms| 11ms | 2ms | 22.395
| |  P99| 24ms| 113ms | 89ms | 366.302
| PreferenceStore.DeleteCategoryAndName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.476
| PreferenceStore.Save |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 25ms| 31ms | 6ms | 24.239
| ProductNoticesStore.ClearOldNotices |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 18ms| 19ms | 1ms | 5.470
| |  P99| 86ms| 87ms | 1ms | 1.157
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 2ms| 4ms | 2ms | 117.586
| |  P99| 5ms| 46ms | 41ms | 828.283
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| SessionStore.Get |  Avg| 3ms| 4ms | 1ms | 30.465
| |  P99| 22ms| 24ms | 2ms | 9.182
| SessionStore.GetLRUSessions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.974
| SessionStore.GetSessionsExpired |  Avg| 2ms| 3ms | 1ms | 59.997
| |  P99| 5ms| 10ms | 5ms | 101.010
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| SessionStore.Remove |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.375
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| SharedChannelStore.HasChannel |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| StatusStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 2ms| 13ms | 11ms | 466.941
| |  P99| 9ms| 234ms | 225ms | 2583.835
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 1ms| 2ms | 1ms | 94.808
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.UpdateLastActivityAt |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 58.889
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 17.157
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 14ms | 4ms | 40.432
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.002
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 11ms | -3ms | -21.924
| TeamStore.GetTeamsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.632
| TeamStore.GetTotalMemberCount |  Avg| 20ms| 19ms | -1ms | -5.023
| |  P99| 25ms| 25ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| ThreadStore.Get |  Avg| 2ms| 1ms | -1ms | -65.691
| |  P99| 7ms| 5ms | -2ms | -27.782
| ThreadStore.GetMembershipForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.569
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.593
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 2ms | 1ms | 68.116
| |  P99| 7ms| 8ms | 1ms | 14.987
| ThreadStore.GetThreadForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 12ms | 1ms | 9.308
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 11ms | -2ms | -15.493
| ThreadStore.GetTotalUnreadThreads |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 12ms | 2ms | 19.729
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 12ms| 12ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 3ms| 4ms | 1ms | 29.086
| |  P99| 10ms| 11ms | 1ms | 10.283
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 1ms | -1ms | -54.119
| |  P99| 8ms| 5ms | -3ms | -36.146
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.099
| ThreadStore.UpdateMembership |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 2ms | 1ms | 70.353
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 163ms| 183ms | 20ms | 12.285
| UserStore.Count |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.282
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.735
| UserStore.GetAllProfiles |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.034
| UserStore.GetAllProfilesInChannel |  Avg| 134ms| 140ms | 6ms | 4.464
| |  P99| 445ms| 454ms | 9ms | 2.022
| UserStore.GetByUsername |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -35.503
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.377
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 10ms | 2ms | 24.487
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.673
| UserStore.GetProfilesInChannel |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 11ms| 13ms | 2ms | 18.155
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| UserStore.Save |  Avg| 64ms| 64ms | 0s | 0.000
| |  P99| 139ms| 134ms | -5ms | -3.608
| UserStore.Search |  Avg| 26ms| 26ms | 0s | 0.000
| |  P99| 50ms| 50ms | 0s | 0.000
| UserStore.Update |  Avg| 5ms| 7ms | 2ms | 41.486
| |  P99| 17ms| 75ms | 58ms | 337.236
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.405
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.807
| UserTermsOfServiceStore.GetByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 13ms | 3ms | 30.267
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 26ms| 27ms | 1ms | 3.793
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 159ms| 150ms | -9ms | -5.645
| | P99| 433ms| 406ms | -27ms | -6.234
| addTeamMember | Avg| 505ms| 520ms | 15ms | 2.973
| | P99| 993ms| 996ms | 3ms | 0.302
| autocompleteChannelsForTeamForSearch | Avg| 28ms| 18ms | -10ms | -35.703
| | P99| 94ms| 71ms | -23ms | -24.449
| autocompleteUsers | Avg| 32ms| 33ms | 1ms | 3.125
| | P99| 136ms| 164ms | 28ms | 20.622
| createChannel | Avg| 141ms| 198ms | 57ms | 40.410
| | P99| 249ms| 249ms | 0s | 0.000
| createChannelBookmark | Avg| 12ms| 10ms | -2ms | -16.759
| | P99| 25ms| 25ms | 0s | 0.000
| createDirectChannel | Avg| 144ms| 153ms | 9ms | 6.270
| | P99| 249ms| 448ms | 199ms | 79.764
| createGroupChannel | Avg| 246ms| 229ms | -17ms | -6.919
| | P99| 496ms| 496ms | 0s | 0.000
| createPost | Avg| 152ms| 157ms | 5ms | 3.280
| | P99| 497ms| 517ms | 20ms | 4.024
| createUser | Avg| 104ms| 104ms | 0s | 0.000
| | P99| 247ms| 247ms | 0s | 0.000
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 7ms| 7ms | 0s | 0.000
| deletePost | Avg| 14ms| 15ms | 1ms | 7.061
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 10ms| 9ms | -1ms | -9.709
| | P99| 24ms| 10ms | -14ms | -57.912
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 16ms| 17ms | 1ms | 6.373
| getCategoriesForTeamForUser | Avg| 12ms| 10ms | -2ms | -16.560
| | P99| 41ms| 40ms | -1ms | -2.455
| getChannel | Avg| 4ms| 5ms | 1ms | 25.603
| | P99| 9ms| 44ms | 35ms | 382.487
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 34ms| 34ms | 0s | 0.000
| getChannelMembers | Avg| 3ms| 0s | -3ms | -104.756
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 14ms | 1ms | 7.758
| getChannelStats | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| getChannelUnread | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 9ms | 4ms | 80.808
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 11ms| 12ms | 1ms | 8.755
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 20ms| 5ms | -15ms | -76.523
| getClientConfig | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getFilePreview | Avg| 38ms| 38ms | 0s | 0.000
| | P99| 99ms| 97ms | -2ms | -2.024
| getFileThumbnail | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 87ms| 88ms | 1ms | 1.150
| getPostThread | Avg| 9ms| 8ms | -1ms | -11.635
| | P99| 25ms| 24ms | -1ms | -4.036
| getPostsForChannel | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 108ms| 103ms | -5ms | -4.629
| getPostsForChannelAroundLastUnread | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 49ms| 48ms | -1ms | -2.059
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.379
| getProfileImage | Avg| 69ms| 72ms | 3ms | 4.320
| | P99| 290ms| 342ms | 52ms | 17.902
| getPublicChannelsForTeam | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 39ms | 14ms | 56.003
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.345
| getTeamStats | Avg| 36ms| 36ms | 0s | 0.000
| | P99| 50ms| 50ms | 0s | 0.000
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 14ms| 11ms | -3ms | -21.671
| getTeamsUnreadForUser | Avg| 3ms| 4ms | 1ms | 29.553
| | P99| 20ms| 21ms | 1ms | 5.081
| getThreadsForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 14ms| 14ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 20ms | 1ms | 5.346
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 19ms| 19ms | 0s | 0.000
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 8ms| 8ms | 0s | 0.000
| login | Avg| 50ms| 50ms | 0s | 0.000
| | P99| 233ms| 235ms | 2ms | 0.859
| logout | Avg| 20ms| 20ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| patchPost | Avg| 19ms| 21ms | 2ms | 10.705
| | P99| 25ms| 113ms | 88ms | 354.044
| removeUserCustomStatus | Avg| 105ms| 111ms | 6ms | 5.739
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| searchAllChannels | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 98ms| 98ms | 0s | 0.000
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 18ms| 20ms | 2ms | 11.198
| searchPostsInTeam | Avg| 30ms| 29ms | -1ms | -3.348
| | P99| 496ms| 490ms | -6ms | -1.209
| searchUsers | Avg| 27ms| 27ms | 0s | 0.000
| | P99| 50ms| 52ms | 2ms | 4.006
| setPostReminder | Avg| 14ms| 16ms | 2ms | 14.655
| | P99| 25ms| 49ms | 24ms | 96.579
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.218
| updateCategoriesForTeamForUser | Avg| 41ms| 43ms | 2ms | 4.871
| | P99| 96ms| 98ms | 2ms | 2.094
| updatePreferences | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 12ms| 13ms | 1ms | 8.489
| updateReadStateAllThreadsByUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 31ms| 31ms | 0s | 0.000
| | P99| 71ms| 71ms | 0s | 0.000
| updateUserCustomStatus | Avg| 1ms| 0s | -1ms | -145.877
| | P99| 33ms| 5ms | -28ms | -84.836
| uploadFileStream | Avg| 386ms| 400ms | 14ms | 3.628
| | P99| 985ms| 989ms | 4ms | 0.406
| upsertDraft | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000

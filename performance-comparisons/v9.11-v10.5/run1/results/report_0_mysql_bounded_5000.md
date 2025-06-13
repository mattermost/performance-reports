### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | avg | 87ms | 293ms | 206ms | 235.63
| JobStore.UpdateStatusOptimistically | avg | 4ms | 8ms | 4ms | 98.62
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 8ms | 11ms | 3ms | 39.11
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 13ms | 17ms | 4ms | 30.26
| PostStore.SearchPostsForUser | avg | 66ms | 77ms | 11ms | 16.79
| PostStore.Delete | avg | 12ms | 14ms | 2ms | 16.42
| UserStore.Save | avg | 72ms | 74ms | 2ms | 2.78
| ChannelStore.Autocomplete | avg | 952ms | 966ms | 14ms | 1.47
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.AutocompleteInTeamForSearch | p99 | 248ms | 2.422s | 2.174s | 875.97
| JobStore.UpdateOptimistically | p99 | 5ms | 18ms | 13ms | 262.63
| ChannelStore.GetPublicChannelsForTeam | p99 | 10ms | 23ms | 13ms | 130.62
| PostStore.GetPostReminders | p99 | 10ms | 22ms | 12ms | 120.60
| StatusStore.UpdateExpiredDNDStatuses | p99 | 10ms | 22ms | 12ms | 120.60
| SessionStore.Remove | p99 | 5ms | 10ms | 5ms | 101.01
| JobStore.Save | p99 | 9ms | 18ms | 9ms | 97.65
| JobStore.UpdateStatusOptimistically | p99 | 10ms | 18ms | 8ms | 82.42
| PostStore.GetPostReminderMetadata | p99 | 5ms | 9ms | 4ms | 80.81
| FileInfoStore.AttachToPost | p99 | 10ms | 17ms | 7ms | 70.15
| JobStore.GetCountByStatusAndType | p99 | 5ms | 8ms | 3ms | 60.61
| JobStore.UpdateStatus | p99 | 5ms | 8ms | 3ms | 60.61
| ChannelStore.CreateDirectChannel | p99 | 25ms | 40ms | 15ms | 60.36
| TeamStore.GetMember | p99 | 5ms | 8ms | 3ms | 60.32
| ThreadStore.MaintainMembership | p99 | 11ms | 17ms | 6ms | 53.14
| WebhookStore.GetOutgoingByTeam | p99 | 10ms | 15ms | 5ms | 51.86
| UserStore.Save | p99 | 100ms | 135ms | 35ms | 35.06
| PostStore.Update | p99 | 29ms | 32ms | 3ms | 10.17
| PreferenceStore.Save | p99 | 32ms | 35ms | 3ms | 9.35
| PostStore.SearchPostsForUser | p99 | 483ms | 489ms | 6ms | 1.24
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 7ms | 0s | -7ms | -101.99
| ChannelStore.GetAllChannelMembersForUser | avg | 6ms | 2ms | -4ms | -68.33
| StatusStore.SaveOrUpdate | avg | 20ms | 8ms | -12ms | -59.28
| LinkMetadataStore.Save | avg | 4ms | 2ms | -2ms | -47.61
| ChannelStore.GetSidebarCategory | avg | 5ms | 3ms | -2ms | -38.41
| ChannelStore.GetMemberCount | avg | 77ms | 62ms | -15ms | -19.37
| UserStore.GetAllProfilesInChannel | avg | 238ms | 201ms | -37ms | -15.56
| UserStore.Count | avg | 59ms | 50ms | -9ms | -15.20
| ChannelStore.UpdateSidebarCategories | avg | 31ms | 28ms | -3ms | -9.81
| TeamStore.GetTotalMemberCount | avg | 77ms | 74ms | -3ms | -3.92
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 24ms | 0s | -24ms | -98.32
| LinkMetadataStore.Save | p99 | 22ms | 5ms | -17ms | -76.75
| ChannelStore.GetAllChannelMembersForUser | p99 | 28ms | 10ms | -18ms | -64.60
| TeamStore.GetTeamsByUserId | p99 | 10ms | 6ms | -4ms | -41.89
| StatusStore.SaveOrUpdate | p99 | 232ms | 159ms | -73ms | -31.40
| FileInfoStore.GetByIds | p99 | 10ms | 7ms | -3ms | -30.91
| StatusStore.Get | p99 | 7ms | 5ms | -2ms | -28.37
| UserStore.GetUnreadCount | p99 | 21ms | 15ms | -6ms | -28.22
| GroupStore.GetByName | p99 | 8ms | 6ms | -2ms | -24.00
| SessionStore.GetLRUSessions | p99 | 8ms | 6ms | -2ms | -23.89
| TeamStore.GetTeamsForUser | p99 | 8ms | 6ms | -2ms | -23.72
| FileInfoStore.SetContent | p99 | 27ms | 21ms | -6ms | -22.43
| ChannelStore.GetChannelsByUser | p99 | 9ms | 7ms | -2ms | -22.18
| PreferenceStore.GetAll | p99 | 15ms | 12ms | -3ms | -20.30
| ChannelStore.GetSidebarCategory | p99 | 10ms | 8ms | -2ms | -20.13
| UserStore.UpdateUpdateAt | p99 | 17ms | 14ms | -3ms | -17.42
| ChannelStore.SaveMember | p99 | 63ms | 57ms | -6ms | -9.56
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | avg | 87ms | 293ms | 206ms | 235.47
| viewChannel | avg | 9ms | 11ms | 2ms | 21.46
| searchPostsInTeam | avg | 70ms | 82ms | 12ms | 17.22
| autocompleteUsers | avg | 110ms | 112ms | 2ms | 1.81
| searchAllChannels | avg | 952ms | 966ms | 14ms | 1.47
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 248ms | 2.422s | 2.174s | 875.97
| getPostThread | p99 | 20ms | 22ms | 2ms | 10.20
| getPublicChannelsForTeam | p99 | 21ms | 23ms | 2ms | 9.49
| autocompleteUsers | p99 | 308ms | 319ms | 11ms | 3.57
| getPostsForChannel | p99 | 89ms | 92ms | 3ms | 3.36
| searchPostsInTeam | p99 | 485ms | 493ms | 8ms | 1.65
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createPost | avg | 272ms | 162ms | -110ms | -40.43
| getChannel | avg | 6ms | 4ms | -2ms | -33.78
| logout | avg | 29ms | 21ms | -8ms | -27.58
| updateCategoriesForTeamForUser | avg | 43ms | 35ms | -8ms | -18.73
| login | avg | 71ms | 59ms | -12ms | -16.98
| createDirectChannel | avg | 181ms | 153ms | -28ms | -15.47
| updateReadStateThreadByUser | avg | 21ms | 18ms | -3ms | -14.54
| createGroupChannel | avg | 245ms | 214ms | -31ms | -12.64
| addTeamMember | avg | 755ms | 671ms | -84ms | -11.12
| removeUserCustomStatus | avg | 102ms | 92ms | -10ms | -9.85
| patchPost | avg | 26ms | 24ms | -2ms | -7.81
| createChannel | avg | 204ms | 190ms | -14ms | -6.87
| createUser | avg | 117ms | 111ms | -6ms | -5.11
| uploadFileStream | avg | 478ms | 454ms | -24ms | -5.02
| addChannelMember | avg | 156ms | 151ms | -5ms | -3.21
| getTeamStats | avg | 101ms | 98ms | -3ms | -2.97
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getTeamStats | p99 | 247ms | 100ms | -147ms | -59.51
| patchPost | p99 | 127ms | 63ms | -64ms | -50.40
| createDirectChannel | p99 | 449ms | 248ms | -201ms | -44.73
| uploadFileStream | p99 | 1.562s | 991ms | -571ms | -36.56
| getTeamsForUser | p99 | 10ms | 7ms | -3ms | -30.92
| login | p99 | 331ms | 245ms | -86ms | -25.99
| getUser | p99 | 12ms | 9ms | -3ms | -25.54
| updateReadStateThreadByUser | p99 | 40ms | 31ms | -9ms | -22.30
| saveReaction | p99 | 13ms | 10ms | -3ms | -22.25
| getChannelsForUser | p99 | 9ms | 7ms | -2ms | -21.63
| getPreferences | p99 | 15ms | 13ms | -2ms | -13.18
| addChannelMember | p99 | 270ms | 248ms | -22ms | -8.15
| addTeamMember | p99 | 2.393s | 2.234s | -159ms | -6.64
| getChannelStats | p99 | 218ms | 204ms | -14ms | -6.43
| getPostsForChannelAroundLastUnread | p99 | 57ms | 54ms | -3ms | -5.27
| createPost | p99 | 926ms | 878ms | -48ms | -5.18
| getFileThumbnail | p99 | 89ms | 87ms | -2ms | -2.25
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.941
| BotStore.Get |  Avg| 1ms| 2ms | 1ms | 71.022
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 13ms| 14ms | 1ms | 7.419
| ChannelStore.Autocomplete |  Avg| 952ms| 966ms | 14ms | 1.471
| |  P99| 2.459s| 2.461s | 2ms | 0.081
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 87ms| 293ms | 206ms | 235.634
| |  P99| 248ms| 2.422s | 2.174s | 875.975
| ChannelStore.CreateDirectChannel |  Avg| 18ms| 19ms | 1ms | 5.525
| |  P99| 25ms| 40ms | 15ms | 60.362
| ChannelStore.CreateInitialSidebarCategories |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 48ms| 47ms | -1ms | -2.063
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 7ms| 0s | -7ms | -101.994
| |  P99| 24ms| 0s | -24ms | -98.316
| ChannelStore.GetAllChannelMembersForUser |  Avg| 6ms| 2ms | -4ms | -68.332
| |  P99| 28ms| 10ms | -18ms | -64.597
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 13ms| 17ms | 4ms | 30.264
| |  P99| 95ms| 94ms | -1ms | -1.050
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.606
| ChannelStore.GetChannelUnread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 7ms | -2ms | -22.178
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.182
| ChannelStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.114
| ChannelStore.GetMemberCount |  Avg| 77ms| 62ms | -15ms | -19.370
| |  P99| 247ms| 245ms | -2ms | -0.809
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberLastViewedAt |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.338
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 10.127
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 23ms | 13ms | 130.621
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 22ms| 21ms | -1ms | -4.532
| ChannelStore.GetSidebarCategory |  Avg| 5ms| 3ms | -2ms | -38.407
| |  P99| 10ms| 8ms | -2ms | -20.129
| ChannelStore.GetTeamChannels |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 49ms| 49ms | 0s | 0.000
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.Save |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 71ms| 71ms | 0s | 0.000
| ChannelStore.SaveMember |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 63ms| 57ms | -6ms | -9.565
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 31ms| 28ms | -3ms | -9.809
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.080
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 8ms| 11ms | 3ms | 39.110
| |  P99| 24ms| 25ms | 1ms | 4.149
| DraftStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Upsert |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 17ms | 7ms | 70.148
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 7ms | -3ms | -30.912
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 27ms| 21ms | -6ms | -22.432
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -15.198
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -24.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 0s | -1ms | -84.087
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.GetNewestJobByStatusesAndType |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 18ms | 9ms | 97.649
| JobStore.UpdateOptimistically |  Avg| 3ms| 4ms | 1ms | 30.702
| |  P99| 5ms| 18ms | 13ms | 262.626
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 8ms | 4ms | 98.624
| |  P99| 10ms| 18ms | 8ms | 82.421
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 4ms| 2ms | -2ms | -47.606
| |  P99| 22ms| 5ms | -17ms | -76.749
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.497
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PluginStore.SetWithOptions |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 19ms| 20ms | 1ms | 5.388
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 621ms| 618ms | -3ms | -0.483
| |  P99| 995ms| 995ms | 0s | 0.000
| PostStore.Delete |  Avg| 12ms| 14ms | 2ms | 16.423
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.441
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 2ms | 1ms | 79.560
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostStore.GetPostReminders |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 120.603
| PostStore.GetPosts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 39ms| 39ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 47ms| 47ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 66ms| 77ms | 11ms | 16.792
| |  P99| 483ms| 489ms | 6ms | 1.244
| PostStore.SetPostReminder |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 29ms| 32ms | 3ms | 10.170
| PreferenceStore.DeleteCategoryAndName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 12ms | -3ms | -20.300
| PreferenceStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 32ms| 35ms | 3ms | 9.349
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 30ms| 30ms | 0s | 0.000
| |  P99| 87ms| 88ms | 1ms | 1.149
| ReactionStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.420
| RoleStore.ChannelHigherScopedPermissions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 1ms | 1ms | 306877.763
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 21ms| 21ms | 0s | 0.000
| SessionStore.GetLRUSessions |  Avg| 2ms| 1ms | -1ms | -66.407
| |  P99| 8ms| 6ms | -2ms | -23.890
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 10ms | 5ms | 101.010
| SessionStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 20ms| 19ms | -1ms | -4.920
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 5ms | -2ms | -28.374
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| StatusStore.SaveOrUpdate |  Avg| 20ms| 8ms | -12ms | -59.280
| |  P99| 232ms| 159ms | -73ms | -31.401
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 10ms| 22ms | 12ms | 120.603
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetActiveMemberCount |  Avg| 97ms| 98ms | 1ms | 1.028
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.205
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 13.757
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.325
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 1ms | -1ms | -63.699
| |  P99| 10ms| 6ms | -4ms | -41.894
| TeamStore.GetTeamsForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -23.724
| TeamStore.GetTotalMemberCount |  Avg| 77ms| 74ms | -3ms | -3.915
| |  P99| 100ms| 100ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.343
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.781
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.645
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 11ms| 17ms | 6ms | 53.136
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 3ms | 1ms | 40.425
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.801
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 130ms| 130ms | 0s | 0.000
| |  P99| 344ms| 347ms | 3ms | 0.873
| UserStore.Count |  Avg| 59ms| 50ms | -9ms | -15.196
| |  P99| 99ms| 99ms | 0s | 0.000
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 3ms| 2ms | -1ms | -38.493
| |  P99| 9ms| 9ms | 0s | 0.000
| UserStore.GetAllProfilesInChannel |  Avg| 238ms| 201ms | -37ms | -15.564
| |  P99| 499ms| 497ms | -2ms | -0.401
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.237
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 1ms| 2ms | 1ms | 72.364
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfilesNotInChannel |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 5ms| 6ms | 1ms | 19.847
| |  P99| 21ms| 15ms | -6ms | -28.223
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.Save |  Avg| 72ms| 74ms | 2ms | 2.781
| |  P99| 100ms| 135ms | 35ms | 35.060
| UserStore.Search |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 243ms| 242ms | -1ms | -0.412
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 17ms | 0s | 0.000
| UserStore.UpdateLastLogin |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 14ms| 14ms | 0s | 0.000
| UserStore.UpdateUpdateAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 17ms| 14ms | -3ms | -17.419
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -13.134
| WebhookStore.GetOutgoingByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 15ms | 5ms | 51.859
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 156ms| 151ms | -5ms | -3.214
| | P99| 270ms| 248ms | -22ms | -8.148
| addTeamMember | Avg| 755ms| 671ms | -84ms | -11.125
| | P99| 2.393s| 2.234s | -159ms | -6.644
| autocompleteChannelsForTeamForSearch | Avg| 87ms| 293ms | 206ms | 235.467
| | P99| 248ms| 2.422s | 2.174s | 875.975
| autocompleteUsers | Avg| 110ms| 112ms | 2ms | 1.814
| | P99| 308ms| 319ms | 11ms | 3.566
| createChannel | Avg| 204ms| 190ms | -14ms | -6.873
| | P99| 249ms| 249ms | 0s | 0.000
| createDirectChannel | Avg| 181ms| 153ms | -28ms | -15.468
| | P99| 449ms| 248ms | -201ms | -44.729
| createGroupChannel | Avg| 245ms| 214ms | -31ms | -12.645
| | P99| 496ms| 493ms | -3ms | -0.605
| createPost | Avg| 272ms| 162ms | -110ms | -40.426
| | P99| 926ms| 878ms | -48ms | -5.183
| createUser | Avg| 117ms| 111ms | -6ms | -5.112
| | P99| 249ms| 248ms | -1ms | -0.402
| deleteDraft | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 7ms | 1ms | 15.543
| deletePost | Avg| 19ms| 20ms | 1ms | 5.375
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 11ms| 10ms | -1ms | -9.432
| | P99| 25ms| 25ms | 0s | 0.000
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.179
| getCategoriesForTeamForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getChannel | Avg| 6ms| 4ms | -2ms | -33.776
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelMember | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 21ms| 21ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelMembersForUser | Avg| 2ms| 3ms | 1ms | 46.516
| | P99| 10ms| 11ms | 1ms | 10.113
| getChannelStats | Avg| 8ms| 7ms | -1ms | -12.242
| | P99| 218ms| 204ms | -14ms | -6.432
| getChannelUnread | Avg| 2ms| 1ms | -1ms | -56.916
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 7ms | -2ms | -21.634
| getClientConfig | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 23ms| 23ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 38ms| 37ms | -1ms | -2.657
| | P99| 95ms| 94ms | -1ms | -1.056
| getFileThumbnail | Avg| 32ms| 31ms | -1ms | -3.168
| | P99| 89ms| 87ms | -2ms | -2.251
| getPostThread | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 20ms| 22ms | 2ms | 10.200
| getPostsForChannel | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 89ms| 92ms | 3ms | 3.362
| getPostsForChannelAroundLastUnread | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 57ms| 54ms | -3ms | -5.273
| getPreferences | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 15ms| 13ms | -2ms | -13.182
| getProfileImage | Avg| 86ms| 86ms | 0s | 0.000
| | P99| 439ms| 438ms | -1ms | -0.228
| getPublicChannelsForTeam | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 21ms| 23ms | 2ms | 9.487
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -16.000
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 9ms | -1ms | -10.045
| getTeamStats | Avg| 101ms| 98ms | -3ms | -2.972
| | P99| 247ms| 100ms | -147ms | -59.514
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 7ms | -3ms | -30.916
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 20ms| 19ms | -1ms | -4.902
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 9ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 12ms| 9ms | -3ms | -25.536
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 13ms| 12ms | -1ms | -7.412
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listChannelBookmarksForChannel | Avg| 1ms| 2ms | 1ms | 66.810
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 71ms| 59ms | -12ms | -16.984
| | P99| 331ms| 245ms | -86ms | -25.988
| logout | Avg| 29ms| 21ms | -8ms | -27.583
| | P99| 50ms| 49ms | -1ms | -2.010
| patchPost | Avg| 26ms| 24ms | -2ms | -7.809
| | P99| 127ms| 63ms | -64ms | -50.399
| removeUserCustomStatus | Avg| 102ms| 92ms | -10ms | -9.851
| | P99| 247ms| 245ms | -2ms | -0.808
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 13ms| 10ms | -3ms | -22.248
| searchAllChannels | Avg| 952ms| 966ms | 14ms | 1.471
| | P99| 2.459s| 2.461s | 2ms | 0.081
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| searchPostsInTeam | Avg| 70ms| 82ms | 12ms | 17.216
| | P99| 485ms| 493ms | 8ms | 1.648
| searchUsers | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 243ms| 243ms | 0s | 0.000
| setPostReminder | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000
| updateCategoriesForTeamForUser | Avg| 43ms| 35ms | -8ms | -18.728
| | P99| 50ms| 50ms | 0s | 0.000
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| updateReadStateThreadByUser | Avg| 21ms| 18ms | -3ms | -14.545
| | P99| 40ms| 31ms | -9ms | -22.299
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 478ms| 454ms | -24ms | -5.022
| | P99| 1.562s| 991ms | -571ms | -36.559
| upsertDraft | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| viewChannel | Avg| 9ms| 11ms | 2ms | 21.459
| | P99| 25ms| 25ms | 0s | 0.000

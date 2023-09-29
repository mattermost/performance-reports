### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| LinkMetadataStore.Save | avg | 2ms | 4ms | 2ms | 115.33
| StatusStore.SaveOrUpdate | avg | 27ms | 38ms | 11ms | 41.04
| PostStore.SearchPostsForUser | avg | 97ms | 126ms | 29ms | 29.98
| ChannelStore.Save | avg | 10ms | 13ms | 3ms | 29.25
| PreferenceStore.Save | avg | 9ms | 11ms | 2ms | 22.95
| ChannelStore.GetMembers | avg | 77ms | 85ms | 8ms | 10.36
| ChannelStore.AutocompleteInTeamForSearch | avg | 272ms | 292ms | 20ms | 7.34
| ChannelStore.UpdateSidebarCategories | avg | 27ms | 29ms | 2ms | 7.33
| PostStore.AnalyticsPostCount | avg | 3.668s | 3.744s | 76ms | 2.07
| UserStore.AutocompleteUsersInChannel | avg | 130ms | 132ms | 2ms | 1.54
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostStore.SearchPostsForUser | p99 | 735ms | 3.031s | 2.296s | 312.43
| ChannelStore.Save | p99 | 25ms | 89ms | 64ms | 259.63
| StatusStore.GetByIds | p99 | 5ms | 16ms | 11ms | 222.22
| UserStore.Count | p99 | 99ms | 233ms | 134ms | 134.76
| JobStore.GetAllByStatus | p99 | 8ms | 18ms | 10ms | 118.97
| PostAcknowledgementStore.GetForPost | p99 | 9ms | 18ms | 9ms | 103.16
| LinkMetadataStore.Save | p99 | 5ms | 9ms | 4ms | 80.05
| ChannelStore.GetChannelsByUser | p99 | 5ms | 8ms | 3ms | 60.61
| PreferenceStore.Save | p99 | 32ms | 44ms | 12ms | 37.98
| PostStore.Update | p99 | 46ms | 60ms | 14ms | 30.40
| ChannelStore.GetPublicChannelsForTeam | p99 | 23ms | 30ms | 7ms | 30.24
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 9ms | 11ms | 2ms | 22.70
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 9ms | 11ms | 2ms | 21.52
| UserStore.Save | p99 | 140ms | 168ms | 28ms | 19.96
| StatusStore.Get | p99 | 12ms | 14ms | 2ms | 16.20
| UserStore.GetForLogin | p99 | 15ms | 17ms | 2ms | 13.01
| FileInfoStore.Save | p99 | 16ms | 18ms | 2ms | 12.66
| StatusStore.UpdateExpiredDNDStatuses | p99 | 22ms | 24ms | 2ms | 8.91
| StatusStore.SaveOrUpdate | p99 | 440ms | 456ms | 16ms | 3.63
| UserStore.GetAllProfilesInChannel | p99 | 900ms | 911ms | 11ms | 1.22
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.DeleteForPost | avg | 5ms | 0s | -5ms | -104.13
| ThreadStore.MarkAllAsReadByTeam | avg | 6ms | 0s | -6ms | -103.37
| PostPersistentNotificationStore.UpdateLastActivity | avg | 4ms | 0s | -4ms | -102.44
| ChannelStore.GetChannelUnread | avg | 3ms | 1ms | -2ms | -79.86
| UserStore.GetAllProfiles | avg | 8ms | 3ms | -5ms | -58.84
| UserStore.GetUnreadCount | avg | 14ms | 12ms | -2ms | -14.15
| UserStore.Count | avg | 74ms | 66ms | -8ms | -10.81
| ChannelStore.GetTeamChannels | avg | 26ms | 24ms | -2ms | -7.68
| UserStore.GetAllProfilesInChannel | avg | 270ms | 267ms | -3ms | -1.11
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetMany | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.01
| PostStore.GetPostsByIds | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetChannelsByIds | p99 | 5ms | 0s | -5ms | -101.01
| FileInfoStore.DeleteForPost | p99 | 5ms | 0s | -5ms | -100.95
| ThreadStore.MarkAllAsReadByTeam | p99 | 10ms | 0s | -10ms | -100.50
| UserStore.GetAllProfiles | p99 | 219ms | 18ms | -201ms | -91.68
| ChannelStore.GetChannelUnread | p99 | 44ms | 5ms | -39ms | -87.64
| PreferenceStore.DeleteCategoryAndName | p99 | 24ms | 5ms | -19ms | -79.58
| ChannelStore.GetTeamChannels | p99 | 50ms | 25ms | -25ms | -50.25
| JobStore.UpdateStatus | p99 | 18ms | 9ms | -9ms | -49.72
| ChannelStore.CreateDirectChannel | p99 | 94ms | 50ms | -44ms | -46.56
| PostStore.Delete | p99 | 46ms | 25ms | -21ms | -45.41
| ChannelStore.SearchGroupChannels | p99 | 9ms | 5ms | -4ms | -44.94
| PostStore.GetPostsAfter | p99 | 9ms | 5ms | -4ms | -43.70
| UserStore.IsEmpty | p99 | 8ms | 5ms | -3ms | -38.51
| PluginStore.List | p99 | 8ms | 5ms | -3ms | -36.58
| PostStore.GetPostIdAfterTime | p99 | 15ms | 10ms | -5ms | -33.18
| GroupStore.GetByName | p99 | 17ms | 12ms | -5ms | -30.00
| TeamStore.GetTeamsForUser | p99 | 17ms | 12ms | -5ms | -29.70
| UserStore.Update | p99 | 18ms | 13ms | -5ms | -27.71
| ThreadStore.GetThreadFollowers | p99 | 8ms | 6ms | -2ms | -26.02
| UserStore.GetUnreadCount | p99 | 644ms | 497ms | -147ms | -22.83
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 32ms | 25ms | -7ms | -21.81
| ChannelStore.CreateInitialSidebarCategories | p99 | 70ms | 55ms | -15ms | -21.43
| SessionStore.Get | p99 | 33ms | 26ms | -7ms | -21.07
| PostStore.Get | p99 | 12ms | 10ms | -2ms | -16.19
| ThreadStore.GetThreadForUser | p99 | 12ms | 10ms | -2ms | -16.03
| ChannelStore.Autocomplete | p99 | 200ms | 169ms | -31ms | -15.50
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 14ms | 12ms | -2ms | -14.61
| FileInfoStore.SetContent | p99 | 29ms | 25ms | -4ms | -13.56
| TeamStore.GetAllPage | p99 | 15ms | 13ms | -2ms | -13.35
| SystemStore.GetByName | p99 | 15ms | 13ms | -2ms | -13.29
| PreferenceStore.GetAll | p99 | 22ms | 20ms | -2ms | -9.28
| ChannelStore.GetByName | p99 | 27ms | 25ms | -2ms | -7.49
| ChannelStore.SaveMember | p99 | 92ms | 87ms | -5ms | -5.46
| ProductNoticesStore.View | p99 | 147ms | 141ms | -6ms | -4.08
| UserStore.AutocompleteUsersInChannel | p99 | 375ms | 360ms | -15ms | -4.00
| TeamStore.SaveMember | p99 | 135ms | 131ms | -4ms | -2.97
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 107ms | 253ms | 146ms | 136.77
| searchPostsInTeam | avg | 101ms | 131ms | 30ms | 29.59
| setPostReminder | avg | 13ms | 15ms | 2ms | 15.82
| autocompleteChannelsForTeamForSearch | avg | 272ms | 292ms | 20ms | 7.34
| removeUserCustomStatus | avg | 129ms | 138ms | 9ms | 6.98
| autocompleteUsers | avg | 97ms | 102ms | 5ms | 5.14
| updateUserCustomStatus | avg | 138ms | 142ms | 4ms | 2.90
| createUser | avg | 91ms | 93ms | 2ms | 2.19
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchPostsInTeam | p99 | 864ms | 3.031s | 2.167s | 250.69
| unfollowThreadByUser | p99 | 41ms | 80ms | 39ms | 95.12
| patchPost | p99 | 5.301s | 10s | 4.699s | 88.64
| getChannelsForUser | p99 | 5ms | 8ms | 3ms | 60.61
| createGroupChannel | p99 | 497ms | 785ms | 288ms | 57.98
| getChannel | p99 | 17ms | 25ms | 8ms | 46.07
| getTeamMember | p99 | 5ms | 7ms | 2ms | 40.10
| getPublicChannelsForTeam | p99 | 25ms | 30ms | 5ms | 20.27
| followThreadByUser | p99 | 23ms | 25ms | 2ms | 8.57
| getChannelStats | p99 | 176ms | 184ms | 8ms | 4.56
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 3ms | 0s | -3ms | -107.92
| updateReadStateAllThreadsByUser | avg | 6ms | 0s | -6ms | -102.11
| getChannelUnread | avg | 3ms | 1ms | -2ms | -70.23
| getUsers | avg | 10ms | 5ms | -5ms | -49.58
| getPostsForChannel | avg | 19ms | 16ms | -3ms | -16.00
| deletePost | avg | 19ms | 17ms | -2ms | -10.70
| createChannel | avg | 26ms | 24ms | -2ms | -7.64
| getFilePreview | avg | 37ms | 35ms | -2ms | -5.41
| addChannelMember | avg | 203ms | 195ms | -8ms | -3.95
| getProfileImage | avg | 102ms | 98ms | -4ms | -3.91
| createDirectChannel | avg | 209ms | 201ms | -8ms | -3.83
| login | avg | 62ms | 60ms | -2ms | -3.22
| uploadFileStream | avg | 418ms | 407ms | -11ms | -2.63
| addTeamMember | avg | 840ms | 826ms | -14ms | -1.67
| createGroupChannel | avg | 288ms | 284ms | -4ms | -1.39
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 5ms | 0s | -5ms | -101.01
| updateReadStateAllThreadsByUser | p99 | 10ms | 0s | -10ms | -100.50
| getUsers | p99 | 222ms | 24ms | -198ms | -89.34
| getChannelUnread | p99 | 44ms | 5ms | -39ms | -87.64
| createChannel | p99 | 50ms | 25ms | -25ms | -50.25
| deletePost | p99 | 46ms | 25ms | -21ms | -45.41
| updateCategoriesForTeamForUser | p99 | 91ms | 50ms | -41ms | -45.28
| getPostsForChannel | p99 | 189ms | 125ms | -64ms | -33.81
| searchGroupChannels | p99 | 9ms | 6ms | -3ms | -33.25
| getCategoriesForTeamForUser | p99 | 33ms | 25ms | -8ms | -24.01
| createPost | p99 | 2.049s | 1.617s | -432ms | -21.09
| getChannelsForTeamForUser | p99 | 17ms | 14ms | -3ms | -18.16
| getFilePreview | p99 | 190ms | 156ms | -34ms | -17.92
| getClientConfig | p99 | 36ms | 30ms | -6ms | -16.82
| searchAllChannels | p99 | 200ms | 169ms | -31ms | -15.50
| getTeamMembersForUser | p99 | 22ms | 19ms | -3ms | -13.60
| autocompleteUsers | p99 | 319ms | 303ms | -16ms | -5.01
| getChannelMember | p99 | 41ms | 39ms | -2ms | -4.91
| addChannelMember | p99 | 500ms | 479ms | -21ms | -4.20
| getPostsForChannelAroundLastUnread | p99 | 85ms | 83ms | -2ms | -2.36
| getFileThumbnail | p99 | 94ms | 92ms | -2ms | -2.13
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 23ms | 0s | 0.000
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.Autocomplete |  Avg| 43ms| 42ms | -1ms | -2.314
| |  P99| 200ms| 169ms | -31ms | -15.499
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 272ms| 292ms | 20ms | 7.341
| |  P99| 2.425s| 2.424s | -1ms | -0.041
| ChannelStore.CreateDirectChannel |  Avg| 20ms| 19ms | -1ms | -5.009
| |  P99| 94ms| 50ms | -44ms | -46.565
| ChannelStore.CreateInitialSidebarCategories |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 70ms| 55ms | -15ms | -21.428
| ChannelStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| ChannelStore.GetByName |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 25ms | -2ms | -7.493
| ChannelStore.GetChannelUnread |  Avg| 3ms| 1ms | -2ms | -79.862
| |  P99| 44ms| 5ms | -39ms | -87.642
| ChannelStore.GetChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.157
| ChannelStore.GetChannelsByIds |  Avg| 1ms| 0s | -1ms | -98.191
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelsByUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 8ms | 3ms | 60.606
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetFileCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 12.191
| ChannelStore.GetGuestCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 62ms| 62ms | 0s | 0.000
| |  P99| 242ms| 243ms | 1ms | 0.413
| ChannelStore.GetMemberForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 77ms| 85ms | 8ms | 10.356
| |  P99| 248ms| 247ms | -1ms | -0.403
| ChannelStore.GetMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetPinnedPostCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ChannelStore.GetPublicChannelsForTeam |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 23ms| 30ms | 7ms | 30.242
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 32ms| 25ms | -7ms | -21.815
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.327
| ChannelStore.GetTeamChannels |  Avg| 26ms| 24ms | -2ms | -7.682
| |  P99| 50ms| 25ms | -25ms | -50.251
| ChannelStore.IncrementMentionCount |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 13ms| 13ms | 0s | 0.000
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 10ms| 13ms | 3ms | 29.254
| |  P99| 25ms| 89ms | 64ms | 259.635
| ChannelStore.SaveMember |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 92ms| 87ms | -5ms | -5.456
| ChannelStore.SearchGroupChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.944
| ChannelStore.UpdateLastViewedAt |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 20ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 27ms| 29ms | 2ms | 7.329
| |  P99| 50ms| 50ms | 0s | 0.000
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 2ms | 1ms | 67.668
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.516
| CommandWebhookStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 6ms| 7ms | 1ms | 15.574
| |  P99| 20ms| 21ms | 1ms | 4.884
| FileInfoStore.DeleteForPost |  Avg| 5ms| 0s | -5ms | -104.127
| |  P99| 5ms| 0s | -5ms | -100.955
| FileInfoStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 16ms| 18ms | 2ms | 12.659
| FileInfoStore.SetContent |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 29ms| 25ms | -4ms | -13.560
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 11ms | 2ms | 22.699
| GroupStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 17ms| 12ms | -5ms | -30.000
| GroupStore.GetGroups |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| JobStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetAllByStatus |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 18ms | 10ms | 118.973
| JobStore.GetCountByStatusAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.GetNewestJobByStatusesAndType |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.399
| JobStore.UpdateStatus |  Avg| 5ms| 4ms | -1ms | -21.969
| |  P99| 18ms| 9ms | -9ms | -49.724
| JobStore.UpdateStatusOptimistically |  Avg| 4ms| 5ms | 1ms | 23.087
| |  P99| 9ms| 10ms | 1ms | 10.830
| LinkMetadataStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Save |  Avg| 2ms| 4ms | 2ms | 115.335
| |  P99| 5ms| 9ms | 4ms | 80.050
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 14ms | -1ms | -6.697
| PluginStore.List |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -36.582
| PluginStore.SetWithOptions |  Avg| 6ms| 7ms | 1ms | 15.710
| |  P99| 24ms| 24ms | 0s | 0.000
| PostAcknowledgementStore.GetForPost |  Avg| 1ms| 2ms | 1ms | 73.165
| |  P99| 9ms| 18ms | 9ms | 103.162
| PostAcknowledgementStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 4ms| 0s | -4ms | -102.444
| |  P99| 5ms| 0s | -5ms | -101.010
| PostPriorityStore.GetForPost |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostPriorityStore.GetForPosts |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 3.668s| 3.744s | 76ms | 2.072
| |  P99| 4.975s| 4.975s | 0s | 0.000
| PostStore.Delete |  Avg| 14ms| 13ms | -1ms | -7.050
| |  P99| 46ms| 25ms | -21ms | -45.407
| PostStore.Get |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.193
| PostStore.GetEtag |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 15ms | -1ms | -6.330
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 10ms | -5ms | -33.182
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| PostStore.GetPostReminderMetadata |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostReminders |  Avg| 7ms| 8ms | 1ms | 13.570
| |  P99| 24ms| 24ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 41ms| 42ms | 1ms | 2.426
| PostStore.GetPostsAfter |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -43.700
| PostStore.GetPostsBefore |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 9ms| 9ms | 0s | 0.000
| PostStore.GetPostsByIds |  Avg| 1ms| 0s | -1ms | -87.631
| |  P99| 5ms| 0s | -5ms | -101.010
| PostStore.GetPostsByThread |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 45ms| 45ms | 0s | 0.000
| PostStore.GetSingle |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 48ms| 48ms | 0s | 0.000
| PostStore.SearchPostsForUser |  Avg| 97ms| 126ms | 29ms | 29.979
| |  P99| 735ms| 3.031s | 2.296s | 312.433
| PostStore.SetPostReminder |  Avg| 7ms| 8ms | 1ms | 13.352
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 18ms| 19ms | 1ms | 5.526
| |  P99| 46ms| 60ms | 14ms | 30.397
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 3ms | -1ms | -23.754
| |  P99| 24ms| 5ms | -19ms | -79.582
| PreferenceStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.507
| PreferenceStore.GetAll |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 22ms| 20ms | -2ms | -9.284
| PreferenceStore.Save |  Avg| 9ms| 11ms | 2ms | 22.948
| |  P99| 32ms| 44ms | 12ms | 37.977
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 36ms| 36ms | 0s | 0.000
| |  P99| 147ms| 141ms | -6ms | -4.078
| ReactionStore.GetForPost |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 8ms | -1ms | -11.574
| ReactionStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 33ms| 26ms | -7ms | -21.074
| SessionStore.GetSessionsExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.666
| SessionStore.Remove |  Avg| 4ms| 5ms | 1ms | 22.929
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| SessionStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| StatusStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 12ms| 14ms | 2ms | 16.205
| StatusStore.GetByIds |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 16ms | 11ms | 222.222
| StatusStore.SaveOrUpdate |  Avg| 27ms| 38ms | 11ms | 41.039
| |  P99| 440ms| 456ms | 16ms | 3.633
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 6ms| 7ms | 1ms | 16.363
| |  P99| 22ms| 24ms | 2ms | 8.909
| StatusStore.UpdateLastActivityAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 11ms| 10ms | -1ms | -9.264
| SystemStore.GetByName |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.288
| TeamStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetAllPage |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 15ms| 13ms | -2ms | -13.352
| TeamStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 14ms| 12ms | -2ms | -14.605
| TeamStore.GetMany |  Avg| 1ms| 0s | -1ms | -103.874
| |  P99| 5ms| 0s | -5ms | -101.010
| TeamStore.GetMember |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.614
| TeamStore.GetTeamsForUser |  Avg| 2ms| 1ms | -1ms | -65.787
| |  P99| 17ms| 12ms | -5ms | -29.704
| TeamStore.SaveMember |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 135ms| 131ms | -4ms | -2.971
| ThreadStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.485
| ThreadStore.GetTeamsUnreadForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 16ms| 16ms | 0s | 0.000
| ThreadStore.GetThreadFollowers |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 6ms | -2ms | -26.018
| ThreadStore.GetThreadForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 12ms| 10ms | -2ms | -16.025
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetThreadsForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 8ms| 9ms | 1ms | 11.808
| ThreadStore.GetTotalThreads |  Avg| 1ms| 2ms | 1ms | 69.780
| |  P99| 9ms| 10ms | 1ms | 11.374
| ThreadStore.GetTotalUnreadMentions |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 16ms | 1ms | 6.666
| ThreadStore.GetTotalUnreadThreads |  Avg| 1ms| 2ms | 1ms | 69.074
| |  P99| 9ms| 10ms | 1ms | 11.619
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 1ms| 2ms | 1ms | 66.875
| |  P99| 9ms| 11ms | 2ms | 21.518
| ThreadStore.MaintainMembership |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 20ms| 21ms | 1ms | 4.903
| ThreadStore.MarkAllAsReadByChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByTeam |  Avg| 6ms| 0s | -6ms | -103.368
| |  P99| 10ms| 0s | -10ms | -100.503
| ThreadStore.MarkAsRead |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 130ms| 132ms | 2ms | 1.536
| |  P99| 375ms| 360ms | -15ms | -3.999
| UserStore.Count |  Avg| 74ms| 66ms | -8ms | -10.807
| |  P99| 99ms| 233ms | 134ms | 134.758
| UserStore.Get |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| UserStore.GetAllProfiles |  Avg| 8ms| 3ms | -5ms | -58.838
| |  P99| 219ms| 18ms | -201ms | -91.683
| UserStore.GetAllProfilesInChannel |  Avg| 270ms| 267ms | -3ms | -1.109
| |  P99| 900ms| 911ms | 11ms | 1.223
| UserStore.GetByUsername |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetForLogin |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 15ms| 17ms | 2ms | 13.009
| UserStore.GetMany |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 11ms | 1ms | 9.606
| UserStore.GetProfilesByUsernames |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetUnreadCount |  Avg| 14ms| 12ms | -2ms | -14.148
| |  P99| 644ms| 497ms | -147ms | -22.834
| UserStore.IsEmpty |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -38.507
| UserStore.Save |  Avg| 69ms| 69ms | 0s | 0.000
| |  P99| 140ms| 168ms | 28ms | 19.964
| UserStore.Search |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 242ms| 242ms | 0s | 0.000
| UserStore.Update |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 18ms| 13ms | -5ms | -27.712
| UserStore.UpdateFailedPasswordAttempts |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 23ms| 24ms | 1ms | 4.292
| UserStore.UpdateUpdateAt |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 21ms| 20ms | -1ms | -4.785
| UserTermsOfServiceStore.GetByUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 13ms| 12ms | -1ms | -7.884
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 203ms| 195ms | -8ms | -3.948
| | P99| 500ms| 479ms | -21ms | -4.202
| addTeamMember | Avg| 840ms| 826ms | -14ms | -1.667
| | P99| 2.427s| 2.426s | -1ms | -0.041
| autocompleteChannelsForTeamForSearch | Avg| 272ms| 292ms | 20ms | 7.340
| | P99| 2.425s| 2.424s | -1ms | -0.041
| autocompleteUsers | Avg| 97ms| 102ms | 5ms | 5.141
| | P99| 319ms| 303ms | -16ms | -5.010
| createChannel | Avg| 26ms| 24ms | -2ms | -7.643
| | P99| 50ms| 25ms | -25ms | -50.251
| createDirectChannel | Avg| 209ms| 201ms | -8ms | -3.834
| | P99| 489ms| 488ms | -1ms | -0.205
| createGroupChannel | Avg| 288ms| 284ms | -4ms | -1.389
| | P99| 497ms| 785ms | 288ms | 57.978
| createPost | Avg| 328ms| 328ms | 0s | 0.000
| | P99| 2.049s| 1.617s | -432ms | -21.088
| createUser | Avg| 91ms| 93ms | 2ms | 2.191
| | P99| 241ms| 242ms | 1ms | 0.416
| deletePost | Avg| 19ms| 17ms | -2ms | -10.699
| | P99| 46ms| 25ms | -21ms | -45.407
| followThreadByUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 23ms| 25ms | 2ms | 8.565
| getAllTeams | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 19ms| 18ms | -1ms | -5.212
| getCategoriesForTeamForUser | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 33ms| 25ms | -8ms | -24.007
| getChannel | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 25ms | 8ms | 46.068
| getChannelMember | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 41ms| 39ms | -2ms | -4.909
| getChannelMembers | Avg| 3ms| 0s | -3ms | -107.920
| | P99| 5ms| 0s | -5ms | -101.010
| getChannelMembersForTeamForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 176ms| 184ms | 8ms | 4.556
| getChannelUnread | Avg| 3ms| 1ms | -2ms | -70.233
| | P99| 44ms| 5ms | -39ms | -87.642
| getChannelsForTeamForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 17ms| 14ms | -3ms | -18.163
| getChannelsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 8ms | 3ms | 60.606
| getClientConfig | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 36ms| 30ms | -6ms | -16.821
| getFilePreview | Avg| 37ms| 35ms | -2ms | -5.409
| | P99| 190ms| 156ms | -34ms | -17.919
| getFileThumbnail | Avg| 29ms| 28ms | -1ms | -3.508
| | P99| 94ms| 92ms | -2ms | -2.132
| getPostThread | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| getPostsForChannel | Avg| 19ms| 16ms | -3ms | -16.001
| | P99| 189ms| 125ms | -64ms | -33.813
| getPostsForChannelAroundLastUnread | Avg| 17ms| 16ms | -1ms | -5.972
| | P99| 85ms| 83ms | -2ms | -2.359
| getPreferences | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.539
| getProfileImage | Avg| 102ms| 98ms | -4ms | -3.907
| | P99| 480ms| 483ms | 3ms | 0.625
| getPublicChannelsForTeam | Avg| 10ms| 11ms | 1ms | 9.569
| | P99| 25ms| 30ms | 5ms | 20.267
| getTeamMember | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 7ms | 2ms | 40.100
| getTeamMembersForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 19ms | -3ms | -13.599
| getTeamsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 15ms| 16ms | 1ms | 6.614
| getTeamsUnreadForUser | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 22ms| 21ms | -1ms | -4.586
| getThreadsForUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getUser | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 22ms| 22ms | 0s | 0.000
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 10ms| 5ms | -5ms | -49.584
| | P99| 222ms| 24ms | -198ms | -89.338
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -17.787
| getUsersByNames | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 6ms| 5ms | -1ms | -17.655
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 62ms| 60ms | -2ms | -3.224
| | P99| 248ms| 246ms | -2ms | -0.806
| logout | Avg| 37ms| 38ms | 1ms | 2.685
| | P99| 50ms| 50ms | 0s | 0.000
| patchPost | Avg| 107ms| 253ms | 146ms | 136.769
| | P99| 5.301s| 10s | 4.699s | 88.642
| removeUserCustomStatus | Avg| 129ms| 138ms | 9ms | 6.981
| | P99| 248ms| 248ms | 0s | 0.000
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 44ms| 45ms | 1ms | 2.247
| searchAllChannels | Avg| 43ms| 43ms | 0s | 0.000
| | P99| 200ms| 169ms | -31ms | -15.499
| searchGroupChannels | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 9ms| 6ms | -3ms | -33.252
| searchPostsInTeam | Avg| 101ms| 131ms | 30ms | 29.593
| | P99| 864ms| 3.031s | 2.167s | 250.690
| searchUsers | Avg| 28ms| 28ms | 0s | 0.000
| | P99| 242ms| 242ms | 0s | 0.000
| setPostReminder | Avg| 13ms| 15ms | 2ms | 15.824
| | P99| 25ms| 25ms | 0s | 0.000
| unfollowThreadByUser | Avg| 10ms| 11ms | 1ms | 9.649
| | P99| 41ms| 80ms | 39ms | 95.120
| updateCategoriesForTeamForUser | Avg| 38ms| 39ms | 1ms | 2.637
| | P99| 91ms| 50ms | -41ms | -45.279
| updatePreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 24ms| 24ms | 0s | 0.000
| updateReadStateAllThreadsByUser | Avg| 6ms| 0s | -6ms | -102.108
| | P99| 10ms| 0s | -10ms | -100.503
| updateReadStateThreadByUser | Avg| 21ms| 21ms | 0s | 0.000
| | P99| 48ms| 48ms | 0s | 0.000
| updateUserCustomStatus | Avg| 138ms| 142ms | 4ms | 2.896
| | P99| 248ms| 248ms | 0s | 0.000
| uploadFileStream | Avg| 418ms| 407ms | -11ms | -2.632
| | P99| 996ms| 995ms | -1ms | -0.100
| viewChannel | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 25ms| 25ms | 0s | 0.000

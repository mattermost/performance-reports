### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | avg | 0s | 11ms | 11ms | 1906363.90
| ChannelStore.GetMembers | avg | 7ms | 26ms | 19ms | 282.60
| PreferenceStore.DeleteCategoryAndName | avg | 10ms | 24ms | 14ms | 142.99
| PostStore.Delete | avg | 25ms | 54ms | 29ms | 118.32
| CommandWebhookStore.Cleanup | avg | 5ms | 11ms | 6ms | 112.09
| PostStore.GetPostReminderMetadata | avg | 6ms | 13ms | 7ms | 108.89
| BotStore.Save | avg | 3ms | 6ms | 3ms | 100.11
| ThreadStore.MarkAllAsReadByTeam | avg | 14ms | 26ms | 12ms | 86.74
| TokenStore.Cleanup | avg | 12ms | 20ms | 8ms | 64.01
| LinkMetadataStore.Save | avg | 4ms | 6ms | 2ms | 48.08
| ChannelStore.GetSidebarCategory | avg | 33ms | 48ms | 15ms | 45.66
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 29ms | 42ms | 13ms | 45.01
| ChannelStore.CreateInitialSidebarCategories | avg | 46ms | 66ms | 20ms | 43.75
| SessionStore.Remove | avg | 5ms | 7ms | 2ms | 36.79
| StatusStore.SaveOrUpdate | avg | 17ms | 23ms | 6ms | 34.89
| ChannelStore.SearchGroupChannels | avg | 14ms | 19ms | 5ms | 34.64
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 13ms | 16ms | 3ms | 22.31
| ChannelStore.UpdateSidebarCategories | avg | 138ms | 168ms | 30ms | 21.69
| UserStore.GetByUsername | avg | 10ms | 12ms | 2ms | 19.10
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RoleStore.GetByNames | p99 | 5ms | 49ms | 44ms | 888.88
| ChannelStore.AutocompleteInTeamForSearch | p99 | 435ms | 2.255s | 1.82s | 418.07
| PostStore.GetPostReminderMetadata | p99 | 42ms | 188ms | 146ms | 345.55
| SessionStore.Remove | p99 | 24ms | 86ms | 62ms | 259.69
| PreferenceStore.DeleteCategoryAndName | p99 | 86ms | 223ms | 137ms | 158.38
| CommandWebhookStore.Cleanup | p99 | 10ms | 25ms | 15ms | 151.48
| PostStore.Delete | p99 | 209ms | 455ms | 246ms | 117.42
| LinkMetadataStore.Save | p99 | 21ms | 43ms | 22ms | 107.31
| PostStore.GetPostReminders | p99 | 42ms | 87ms | 45ms | 105.88
| ChannelStore.GetSidebarCategory | p99 | 236ms | 480ms | 244ms | 103.42
| ThreadStore.MarkAllAsReadByTeam | p99 | 49ms | 99ms | 50ms | 102.04
| ChannelStore.GetMembers | p99 | 25ms | 50ms | 25ms | 101.83
| BotStore.Save | p99 | 5ms | 10ms | 5ms | 101.01
| TokenStore.Cleanup | p99 | 49ms | 98ms | 49ms | 100.00
| ChannelStore.CreateSidebarCategory | p99 | 249ms | 490ms | 241ms | 96.95
| UserStore.GetProfilesInChannel | p99 | 238ms | 460ms | 222ms | 93.08
| BotStore.Get | p99 | 24ms | 43ms | 19ms | 78.84
| PostPriorityStore.GetForPost | p99 | 48ms | 84ms | 36ms | 74.41
| UserStore.GetByUsername | p99 | 97ms | 161ms | 64ms | 65.98
| UserStore.Update | p99 | 208ms | 311ms | 103ms | 49.41
| StatusStore.SaveOrUpdate | p99 | 230ms | 332ms | 102ms | 44.39
| PostAcknowledgementStore.GetForPost | p99 | 69ms | 98ms | 29ms | 42.10
| DraftStore.GetDraftsForUser | p99 | 145ms | 173ms | 28ms | 19.34
| ChannelStore.Save | p99 | 346ms | 396ms | 50ms | 14.46
| PostStore.GetPostsAfter | p99 | 92ms | 105ms | 13ms | 14.18
| FileInfoStore.Save | p99 | 142ms | 153ms | 11ms | 7.76
| JobStore.GetAllByStatus | p99 | 164ms | 175ms | 11ms | 6.69
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 86ms | 91ms | 5ms | 5.78
| PluginStore.List | p99 | 160ms | 169ms | 9ms | 5.63
| UserStore.UpdateUpdateAt | p99 | 71ms | 74ms | 3ms | 4.24
| ThreadStore.GetThreadFollowers | p99 | 89ms | 92ms | 3ms | 3.37
| ChannelStore.CreateInitialSidebarCategories | p99 | 449ms | 461ms | 12ms | 2.67
| JobStore.Save | p99 | 80ms | 82ms | 2ms | 2.52
| UserStore.AutocompleteUsersInChannel | p99 | 362ms | 371ms | 9ms | 2.48
| JobStore.GetNewestJobByStatusesAndType | p99 | 92ms | 94ms | 2ms | 2.19
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 230ms | 234ms | 4ms | 1.74
| ChannelStore.UpdateSidebarCategories | p99 | 898ms | 910ms | 12ms | 1.34
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | avg | 31ms | 2ms | -29ms | -93.79
| UserStore.GetMany | avg | 18ms | 5ms | -13ms | -73.33
| EmojiStore.GetMultipleByName | avg | 10ms | 3ms | -7ms | -68.96
| RoleStore.ChannelHigherScopedPermissions | avg | 21ms | 8ms | -13ms | -62.96
| UserStore.GetProfilesNotInChannel | avg | 22ms | 9ms | -13ms | -59.53
| ChannelStore.CreateSidebarCategory | avg | 205ms | 96ms | -109ms | -53.10
| SessionStore.GetSessionsExpired | avg | 6ms | 3ms | -3ms | -51.40
| UserAccessTokenStore.GetByToken | avg | 13ms | 8ms | -5ms | -39.22
| ChannelStore.GetTeamChannels | avg | 50ms | 35ms | -15ms | -30.07
| ThreadStore.MarkAllAsReadByChannels | avg | 11ms | 8ms | -3ms | -27.94
| JobStore.Get | avg | 7ms | 5ms | -2ms | -27.83
| JobStore.UpdateOptimistically | avg | 7ms | 5ms | -2ms | -27.35
| JobStore.UpdateStatus | avg | 7ms | 5ms | -2ms | -26.68
| ProductNoticesStore.ClearOldNotices | avg | 45ms | 34ms | -11ms | -24.50
| PluginStore.List | avg | 12ms | 9ms | -3ms | -24.29
| JobStore.UpdateStatusOptimistically | avg | 9ms | 7ms | -2ms | -21.51
| UserStore.Count | avg | 23ms | 18ms | -5ms | -21.36
| PostStore.AnalyticsPostCount | avg | 599ms | 474ms | -125ms | -20.88
| TeamStore.GetTotalMemberCount | avg | 83ms | 67ms | -16ms | -19.37
| ChannelStore.GetChannelsByUser | avg | 11ms | 9ms | -2ms | -17.49
| ChannelStore.GetChannelUnread | avg | 12ms | 10ms | -2ms | -16.62
| ClusterDiscoveryStore.SetLastPingAt | avg | 13ms | 11ms | -2ms | -15.67
| ChannelStore.GetFileCount | avg | 13ms | 11ms | -2ms | -15.64
| FileInfoStore.AttachToPost | avg | 20ms | 17ms | -3ms | -15.25
| StatusStore.GetByIds | avg | 13ms | 11ms | -2ms | -15.21
| DraftStore.Get | avg | 14ms | 12ms | -2ms | -14.65
| TeamStore.GetActiveMemberCount | avg | 84ms | 72ms | -12ms | -14.26
| UserStore.GetProfilesInChannel | avg | 36ms | 31ms | -5ms | -13.97
| SessionStore.Save | avg | 15ms | 13ms | -2ms | -13.72
| ChannelStore.CreateDirectChannel | avg | 82ms | 71ms | -11ms | -13.46
| PostStore.GetPostsByThread | avg | 16ms | 14ms | -2ms | -12.87
| PostStore.Get | avg | 25ms | 22ms | -3ms | -12.13
| ChannelStore.Get | avg | 17ms | 15ms | -2ms | -12.02
| ChannelStore.GetPublicChannelsForTeam | avg | 33ms | 29ms | -4ms | -11.94
| ThreadStore.MaintainMembership | avg | 22ms | 20ms | -2ms | -9.17
| PostStore.Update | avg | 33ms | 30ms | -3ms | -9.07
| PostStore.Save | avg | 36ms | 33ms | -3ms | -8.37
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 37ms | 34ms | -3ms | -8.07
| PreferenceStore.Save | avg | 25ms | 23ms | -2ms | -7.95
| PostStore.GetPostsSince | avg | 28ms | 26ms | -2ms | -7.26
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 29ms | 27ms | -2ms | -6.96
| UserStore.AutocompleteUsersInChannel | avg | 76ms | 72ms | -4ms | -5.24
| UserStore.GetAllProfilesInChannel | avg | 458ms | 434ms | -24ms | -5.24
| UserStore.Search | avg | 56ms | 54ms | -2ms | -3.59
| ProductNoticesStore.View | avg | 71ms | 69ms | -2ms | -2.80
| ChannelStore.AutocompleteInTeamForSearch | avg | 104ms | 102ms | -2ms | -1.93
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | p99 | 50ms | 5ms | -45ms | -90.45
| UserStore.GetProfilesNotInChannel | p99 | 223ms | 25ms | -198ms | -88.79
| SessionStore.GetSessionsExpired | p99 | 47ms | 9ms | -38ms | -80.85
| UserStore.GetMany | p99 | 233ms | 46ms | -187ms | -80.34
| EmojiStore.GetMultipleByName | p99 | 47ms | 10ms | -37ms | -77.90
| PostStore.SetPostReminder | p99 | 420ms | 98ms | -322ms | -76.67
| RoleStore.ChannelHigherScopedPermissions | p99 | 179ms | 48ms | -131ms | -72.98
| UserAccessTokenStore.GetByToken | p99 | 207ms | 78ms | -129ms | -62.24
| JobStore.GetCountByStatusAndType | p99 | 187ms | 91ms | -96ms | -51.34
| PostPersistentNotificationStore.Get | p99 | 46ms | 23ms | -23ms | -50.09
| PostStore.AnalyticsPostCount | p99 | 995ms | 498ms | -497ms | -49.95
| StatusStore.UpdateExpiredDNDStatuses | p99 | 85ms | 43ms | -42ms | -49.41
| PostPersistentNotificationStore.DeleteExpired | p99 | 75ms | 39ms | -36ms | -47.69
| UserStore.Count | p99 | 92ms | 49ms | -43ms | -46.74
| JobStore.Get | p99 | 79ms | 44ms | -35ms | -44.03
| ClusterDiscoveryStore.SetLastPingAt | p99 | 158ms | 93ms | -65ms | -41.09
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 396ms | 241ms | -155ms | -39.11
| ChannelStore.GetChannelUnread | p99 | 154ms | 95ms | -59ms | -38.37
| FileInfoStore.GetByIds | p99 | 136ms | 93ms | -43ms | -31.69
| ChannelStore.GetPublicChannelsForTeam | p99 | 218ms | 155ms | -63ms | -28.96
| PluginStore.SetWithOptions | p99 | 138ms | 99ms | -39ms | -28.31
| ChannelStore.GetChannelsByUser | p99 | 132ms | 95ms | -37ms | -27.98
| ChannelStore.GetChannels | p99 | 139ms | 101ms | -38ms | -27.38
| UserStore.GetProfileByIds | p99 | 136ms | 103ms | -33ms | -24.22
| SessionStore.Save | p99 | 160ms | 126ms | -34ms | -21.28
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 194ms | 154ms | -40ms | -20.61
| FileInfoStore.Get | p99 | 126ms | 100ms | -26ms | -20.58
| PreferenceStore.Get | p99 | 127ms | 101ms | -26ms | -20.44
| JobStore.UpdateStatusOptimistically | p99 | 80ms | 64ms | -16ms | -20.09
| DraftStore.Delete | p99 | 123ms | 99ms | -24ms | -19.54
| ChannelStore.GetMembersForUser | p99 | 122ms | 100ms | -22ms | -18.00
| ThreadStore.GetTeamsUnreadForUser | p99 | 149ms | 123ms | -26ms | -17.49
| ChannelStore.GetMember | p99 | 117ms | 97ms | -20ms | -17.09
| DraftStore.Upsert | p99 | 131ms | 109ms | -22ms | -16.85
| ChannelStore.GetFileCount | p99 | 113ms | 94ms | -19ms | -16.77
| ChannelStore.SearchGroupChannels | p99 | 151ms | 126ms | -25ms | -16.54
| ThreadStore.GetThreadsForUser | p99 | 149ms | 125ms | -24ms | -16.11
| UserStore.GetProfilesByUsernames | p99 | 135ms | 114ms | -21ms | -15.57
| DraftStore.Get | p99 | 158ms | 134ms | -24ms | -15.16
| PostStore.GetEtag | p99 | 115ms | 99ms | -16ms | -13.90
| PluginStore.Delete | p99 | 65ms | 56ms | -9ms | -13.77
| FileInfoStore.AttachToPost | p99 | 192ms | 168ms | -24ms | -12.51
| PostStore.GetPostsBefore | p99 | 138ms | 121ms | -17ms | -12.28
| PostStore.GetPostsByThread | p99 | 108ms | 95ms | -13ms | -11.98
| ChannelStore.GetPinnedPostCount | p99 | 97ms | 87ms | -10ms | -10.29
| TeamStore.GetMember | p99 | 49ms | 44ms | -5ms | -10.20
| FileInfoStore.GetForPost | p99 | 109ms | 98ms | -11ms | -10.13
| PostStore.Save | p99 | 358ms | 322ms | -36ms | -10.06
| StatusStore.GetByIds | p99 | 154ms | 139ms | -15ms | -9.77
| SessionStore.GetLRUSessions | p99 | 82ms | 74ms | -8ms | -9.70
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 94ms | 85ms | -9ms | -9.55
| ThreadStore.GetThreadUnreadReplyCount | p99 | 107ms | 97ms | -10ms | -9.33
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 87ms | 79ms | -8ms | -9.21
| WebhookStore.GetOutgoingByTeam | p99 | 160ms | 146ms | -14ms | -8.76
| UserStore.UpdateLastLogin | p99 | 76ms | 70ms | -6ms | -7.87
| PostAcknowledgementStore.GetForPosts | p99 | 192ms | 179ms | -13ms | -6.77
| PostPriorityStore.GetForPosts | p99 | 194ms | 181ms | -13ms | -6.70
| StatusStore.Get | p99 | 76ms | 71ms | -5ms | -6.55
| ThreadStore.MarkAsRead | p99 | 93ms | 87ms | -6ms | -6.48
| JobStore.UpdateOptimistically | p99 | 47ms | 44ms | -3ms | -6.44
| ChannelStore.GetAllChannelMembersForUser | p99 | 95ms | 89ms | -6ms | -6.31
| ThreadStore.GetMembershipForUser | p99 | 98ms | 92ms | -6ms | -6.12
| UserStore.UpdateFailedPasswordAttempts | p99 | 88ms | 83ms | -5ms | -5.67
| TeamStore.Get | p99 | 94ms | 89ms | -5ms | -5.34
| EmojiStore.GetByName | p99 | 95ms | 90ms | -5ms | -5.28
| PostStore.GetSingle | p99 | 96ms | 91ms | -5ms | -5.22
| ChannelStore.Get | p99 | 177ms | 168ms | -9ms | -5.07
| JobStore.UpdateStatus | p99 | 43ms | 41ms | -2ms | -4.63
| AuditStore.Save | p99 | 87ms | 83ms | -4ms | -4.60
| UserStore.Get | p99 | 90ms | 86ms | -4ms | -4.44
| ReactionStore.GetForPost | p99 | 91ms | 87ms | -4ms | -4.38
| PostStore.GetPostIdBeforeTime | p99 | 95ms | 91ms | -4ms | -4.23
| LinkMetadataStore.Get | p99 | 97ms | 93ms | -4ms | -4.12
| ThreadStore.MarkAllAsReadByChannels | p99 | 97ms | 93ms | -4ms | -4.12
| SessionStore.Get | p99 | 206ms | 198ms | -8ms | -3.88
| ChannelStore.GetTeamChannels | p99 | 236ms | 227ms | -9ms | -3.81
| ChannelStore.GetMemberLastViewedAt | p99 | 83ms | 80ms | -3ms | -3.62
| ThreadStore.MaintainMembership | p99 | 228ms | 220ms | -8ms | -3.51
| ThreadStore.UpdateMembership | p99 | 91ms | 88ms | -3ms | -3.31
| SessionStore.UpdateLastActivityAt | p99 | 91ms | 88ms | -3ms | -3.29
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 92ms | 89ms | -3ms | -3.27
| ChannelStore.IncrementMentionCount | p99 | 92ms | 89ms | -3ms | -3.26
| ChannelStore.GetGuestCount | p99 | 94ms | 91ms | -3ms | -3.19
| ChannelStore.UpdateLastViewedAt | p99 | 95ms | 92ms | -3ms | -3.16
| PreferenceStore.GetAll | p99 | 96ms | 93ms | -3ms | -3.12
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 99ms | 96ms | -3ms | -3.04
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 68ms | 66ms | -2ms | -2.95
| PostStore.GetPostsSince | p99 | 213ms | 207ms | -6ms | -2.82
| PostStore.GetPostIdAfterTime | p99 | 72ms | 70ms | -2ms | -2.80
| UserStore.GetAllProfilesInChannel | p99 | 2.279s | 2.22s | -59ms | -2.59
| ChannelStore.GetMemberCount | p99 | 202ms | 197ms | -5ms | -2.48
| ChannelStore.CreateDirectChannel | p99 | 487ms | 475ms | -12ms | -2.46
| UserTermsOfServiceStore.GetByUser | p99 | 84ms | 82ms | -2ms | -2.38
| UserStore.GetForLogin | p99 | 87ms | 85ms | -2ms | -2.30
| ProductNoticesStore.View | p99 | 624ms | 610ms | -14ms | -2.24
| TeamStore.GetTeamsByUserId | p99 | 90ms | 88ms | -2ms | -2.21
| PostStore.Get | p99 | 230ms | 225ms | -5ms | -2.18
| StatusStore.UpdateLastActivityAt | p99 | 92ms | 90ms | -2ms | -2.17
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 93ms | 91ms | -2ms | -2.15
| PreferenceStore.Save | p99 | 239ms | 234ms | -5ms | -2.09
| GroupStore.GetGroups | p99 | 96ms | 94ms | -2ms | -2.08
| ThreadStore.GetThreadForUser | p99 | 200ms | 196ms | -4ms | -2.00
| ChannelStore.GetMemberForPost | p99 | 155ms | 152ms | -3ms | -1.93
| TeamStore.GetActiveMemberCount | p99 | 243ms | 239ms | -4ms | -1.64
| PostStore.SearchPostsForUser | p99 | 2.425s | 2.39s | -35ms | -1.44
| UserStore.Search | p99 | 237ms | 234ms | -3ms | -1.26
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 7ms | 27ms | 20ms | 269.37
| updateReadStateAllThreadsByUser | avg | 14ms | 26ms | 12ms | 85.89
| deletePost | avg | 45ms | 79ms | 34ms | 75.04
| getCategoriesForTeamForUser | avg | 30ms | 43ms | 13ms | 43.75
| updateCategoriesForTeamForUser | avg | 212ms | 275ms | 63ms | 29.67
| searchGroupChannels | avg | 15ms | 19ms | 4ms | 27.05
| setPostReminder | avg | 72ms | 82ms | 10ms | 13.97
| logout | avg | 131ms | 138ms | 7ms | 5.34
| removeUserCustomStatus | avg | 425ms | 432ms | 7ms | 1.65
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteChannelsForTeamForSearch | p99 | 443ms | 2.255s | 1.812s | 409.48
| updateUserCustomStatus | p99 | 5ms | 20ms | 15ms | 301.18
| updateReadStateAllThreadsByUser | p99 | 49ms | 99ms | 50ms | 102.04
| getChannelMembers | p99 | 25ms | 50ms | 25ms | 101.83
| createCategoryForTeamForUser | p99 | 249ms | 490ms | 241ms | 96.95
| updateCategoriesForTeamForUser | p99 | 1.585s | 2.095s | 510ms | 32.17
| logout | p99 | 425ms | 477ms | 52ms | 12.24
| deletePost | p99 | 432ms | 478ms | 46ms | 10.64
| unfollowThreadByUser | p99 | 413ms | 454ms | 41ms | 9.93
| removeUserCustomStatus | p99 | 2.085s | 2.25s | 165ms | 7.91
| getDrafts | p99 | 180ms | 194ms | 14ms | 7.76
| getChannelStats | p99 | 110ms | 113ms | 3ms | 2.72
| autocompleteUsers | p99 | 349ms | 358ms | 9ms | 2.58
| getUsers | p99 | 219ms | 222ms | 3ms | 1.37
| getCategoriesForTeamForUser | p99 | 234ms | 237ms | 3ms | 1.28
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMember | avg | 26ms | 12ms | -14ms | -54.83
| createCategoryForTeamForUser | avg | 223ms | 106ms | -117ms | -52.42
| followThreadByUser | avg | 76ms | 46ms | -30ms | -39.48
| createChannel | avg | 913ms | 589ms | -324ms | -35.51
| getChannelUnread | avg | 14ms | 11ms | -3ms | -21.88
| getTeamStats | avg | 107ms | 88ms | -19ms | -17.72
| getChannel | avg | 34ms | 28ms | -6ms | -17.49
| getChannelsForUser | avg | 12ms | 10ms | -2ms | -16.97
| getTeamMember | avg | 13ms | 11ms | -2ms | -14.93
| getChannelsForTeamForUser | avg | 14ms | 12ms | -2ms | -14.62
| updatePreferences | avg | 42ms | 36ms | -6ms | -14.30
| getTeamsUnreadForUser | avg | 17ms | 15ms | -2ms | -12.06
| addChannelMember | avg | 664ms | 587ms | -77ms | -11.60
| getPublicChannelsForTeam | avg | 36ms | 32ms | -4ms | -11.12
| getPostThread | avg | 61ms | 55ms | -6ms | -9.81
| createGroupChannel | avg | 1.274s | 1.155s | -119ms | -9.34
| saveReaction | avg | 38ms | 35ms | -3ms | -7.83
| login | avg | 227ms | 210ms | -17ms | -7.50
| updateReadStateThreadByUser | avg | 142ms | 132ms | -10ms | -7.05
| viewChannel | avg | 45ms | 42ms | -3ms | -6.63
| createPost | avg | 891ms | 834ms | -57ms | -6.40
| getFileThumbnail | avg | 56ms | 53ms | -3ms | -5.37
| createUser | avg | 334ms | 319ms | -15ms | -4.50
| getFilePreview | avg | 68ms | 65ms | -3ms | -4.39
| autocompleteUsers | avg | 71ms | 68ms | -3ms | -4.25
| uploadFileStream | avg | 475ms | 457ms | -18ms | -3.79
| getPostsForChannel | avg | 107ms | 103ms | -4ms | -3.72
| searchUsers | avg | 59ms | 57ms | -2ms | -3.41
| getProfileImage | avg | 84ms | 82ms | -2ms | -2.39
| patchPost | avg | 112ms | 110ms | -2ms | -1.79
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | p99 | 845ms | 243ms | -602ms | -71.24
| setPostReminder | p99 | 840ms | 246ms | -594ms | -70.72
| createChannel | p99 | 4.775s | 2.387s | -2.388s | -50.01
| createDirectChannel | p99 | 3.8s | 2.448s | -1.352s | -35.58
| getChannelsForUser | p99 | 140ms | 98ms | -42ms | -29.93
| getChannelUnread | p99 | 182ms | 128ms | -54ms | -29.63
| getChannel | p99 | 321ms | 243ms | -78ms | -24.33
| getTeamMember | p99 | 167ms | 129ms | -38ms | -22.81
| patchPost | p99 | 830ms | 645ms | -185ms | -22.29
| updatePreferences | p99 | 394ms | 320ms | -74ms | -18.78
| getFileThumbnail | p99 | 308ms | 255ms | -53ms | -17.21
| getChannelMember | p99 | 245ms | 207ms | -38ms | -15.50
| getAllTeams | p99 | 134ms | 114ms | -20ms | -14.87
| getPublicChannelsForTeam | p99 | 238ms | 203ms | -35ms | -14.72
| searchGroupChannels | p99 | 163ms | 140ms | -23ms | -14.11
| saveReaction | p99 | 279ms | 247ms | -32ms | -11.49
| getFilePreview | p99 | 374ms | 335ms | -39ms | -10.43
| getTeamMembersForUser | p99 | 147ms | 132ms | -15ms | -10.21
| getChannelsForTeamForUser | p99 | 168ms | 151ms | -17ms | -10.14
| deleteDraft | p99 | 180ms | 162ms | -18ms | -10.01
| getUsersByNames | p99 | 155ms | 140ms | -15ms | -9.69
| getChannelMembersForTeamForUser | p99 | 151ms | 138ms | -13ms | -8.58
| getThreadsForUser | p99 | 176ms | 162ms | -14ms | -7.95
| getPostsForChannel | p99 | 1.059s | 991ms | -68ms | -6.42
| getTeamsUnreadForUser | p99 | 211ms | 200ms | -11ms | -5.23
| login | p99 | 2.123s | 2.025s | -98ms | -4.62
| getUserStatusesByIds | p99 | 44ms | 42ms | -2ms | -4.55
| addChannelMember | p99 | 2.533s | 2.419s | -114ms | -4.50
| getPostThread | p99 | 475ms | 454ms | -21ms | -4.42
| getUsersByIds | p99 | 47ms | 45ms | -2ms | -4.26
| viewChannel | p99 | 433ms | 418ms | -15ms | -3.47
| updateReadStateThreadByUser | p99 | 905ms | 876ms | -29ms | -3.21
| searchPostsInTeam | p99 | 2.476s | 2.399s | -77ms | -3.11
| getClientConfig | p99 | 239ms | 232ms | -7ms | -2.93
| createUser | p99 | 2.21s | 2.148s | -62ms | -2.81
| upsertDraft | p99 | 192ms | 188ms | -4ms | -2.08
| getPreferences | p99 | 100ms | 98ms | -2ms | -2.00
| uploadFileStream | p99 | 2.188s | 2.148s | -40ms | -1.83
| getUser | p99 | 232ms | 228ms | -4ms | -1.73
| createPost | p99 | 4.665s | 4.587s | -78ms | -1.67
| getTeamStats | p99 | 247ms | 244ms | -3ms | -1.21
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 83ms | -4ms | -4.599
| BotStore.Get |  Avg| 6ms| 5ms | -1ms | -17.336
| |  P99| 24ms| 43ms | 19ms | 78.838
| BotStore.Save |  Avg| 3ms| 6ms | 3ms | 100.109
| |  P99| 5ms| 10ms | 5ms | 101.010
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 68ms| 66ms | -2ms | -2.951
| ChannelStore.Autocomplete |  Avg| 60ms| 59ms | -1ms | -1.658
| |  P99| 238ms| 240ms | 2ms | 0.839
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 104ms| 102ms | -2ms | -1.928
| |  P99| 435ms| 2.255s | 1.82s | 418.073
| ChannelStore.CreateDirectChannel |  Avg| 82ms| 71ms | -11ms | -13.458
| |  P99| 487ms| 475ms | -12ms | -2.463
| ChannelStore.CreateInitialSidebarCategories |  Avg| 46ms| 66ms | 20ms | 43.746
| |  P99| 449ms| 461ms | 12ms | 2.673
| ChannelStore.CreateSidebarCategory |  Avg| 205ms| 96ms | -109ms | -53.099
| |  P99| 249ms| 490ms | 241ms | 96.950
| ChannelStore.Get |  Avg| 17ms| 15ms | -2ms | -12.020
| |  P99| 177ms| 168ms | -9ms | -5.072
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 29ms| 27ms | -2ms | -6.958
| |  P99| 194ms| 154ms | -40ms | -20.606
| ChannelStore.GetAllChannelMembersForUser |  Avg| 12ms| 11ms | -1ms | -8.183
| |  P99| 95ms| 89ms | -6ms | -6.314
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 37ms| 34ms | -3ms | -8.066
| |  P99| 396ms| 241ms | -155ms | -39.115
| ChannelStore.GetByName |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 93ms | 0s | 0.000
| ChannelStore.GetChannelUnread |  Avg| 12ms| 10ms | -2ms | -16.621
| |  P99| 154ms| 95ms | -59ms | -38.375
| ChannelStore.GetChannels |  Avg| 12ms| 11ms | -1ms | -8.187
| |  P99| 139ms| 101ms | -38ms | -27.376
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 9ms | -2ms | -17.494
| |  P99| 132ms| 95ms | -37ms | -27.982
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 11ms| 10ms | -1ms | -9.445
| |  P99| 99ms| 96ms | -3ms | -3.044
| ChannelStore.GetFileCount |  Avg| 13ms| 11ms | -2ms | -15.642
| |  P99| 113ms| 94ms | -19ms | -16.774
| ChannelStore.GetGuestCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 94ms| 91ms | -3ms | -3.189
| ChannelStore.GetMember |  Avg| 12ms| 11ms | -1ms | -8.430
| |  P99| 117ms| 97ms | -20ms | -17.092
| ChannelStore.GetMemberCount |  Avg| 36ms| 35ms | -1ms | -2.791
| |  P99| 202ms| 197ms | -5ms | -2.478
| ChannelStore.GetMemberForPost |  Avg| 17ms| 16ms | -1ms | -6.004
| |  P99| 155ms| 152ms | -3ms | -1.933
| ChannelStore.GetMemberLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 83ms| 80ms | -3ms | -3.622
| ChannelStore.GetMembers |  Avg| 7ms| 26ms | 19ms | 282.598
| |  P99| 25ms| 50ms | 25ms | 101.831
| ChannelStore.GetMembersForUser |  Avg| 13ms| 12ms | -1ms | -7.979
| |  P99| 122ms| 100ms | -22ms | -18.004
| ChannelStore.GetPinnedPostCount |  Avg| 10ms| 9ms | -1ms | -9.573
| |  P99| 97ms| 87ms | -10ms | -10.286
| ChannelStore.GetPublicChannelsForTeam |  Avg| 33ms| 29ms | -4ms | -11.941
| |  P99| 218ms| 155ms | -63ms | -28.958
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 29ms| 42ms | 13ms | 45.011
| |  P99| 230ms| 234ms | 4ms | 1.739
| ChannelStore.GetSidebarCategory |  Avg| 33ms| 48ms | 15ms | 45.665
| |  P99| 236ms| 480ms | 244ms | 103.423
| ChannelStore.GetTeamChannels |  Avg| 50ms| 35ms | -15ms | -30.072
| |  P99| 236ms| 227ms | -9ms | -3.806
| ChannelStore.IncrementMentionCount |  Avg| 9ms| 8ms | -1ms | -11.741
| |  P99| 92ms| 89ms | -3ms | -3.256
| ChannelStore.Save |  Avg| 51ms| 50ms | -1ms | -1.963
| |  P99| 346ms| 396ms | 50ms | 14.458
| ChannelStore.SaveMember |  Avg| 62ms| 62ms | 0s | 0.000
| |  P99| 468ms| 469ms | 1ms | 0.213
| ChannelStore.SearchGroupChannels |  Avg| 14ms| 19ms | 5ms | 34.642
| |  P99| 151ms| 126ms | -25ms | -16.536
| ChannelStore.UpdateLastViewedAt |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 95ms| 92ms | -3ms | -3.156
| ChannelStore.UpdateSidebarCategories |  Avg| 138ms| 168ms | 30ms | 21.695
| |  P99| 898ms| 910ms | 12ms | 1.336
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 9ms| 8ms | -1ms | -11.003
| |  P99| 94ms| 85ms | -9ms | -9.549
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 13ms| 11ms | -2ms | -15.671
| |  P99| 158ms| 93ms | -65ms | -41.087
| CommandWebhookStore.Cleanup |  Avg| 5ms| 11ms | 6ms | 112.086
| |  P99| 10ms| 25ms | 15ms | 151.479
| DesktopTokensStore.DeleteOlderThan |  Avg| 31ms| 2ms | -29ms | -93.793
| |  P99| 50ms| 5ms | -45ms | -90.452
| DraftStore.Delete |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 123ms| 99ms | -24ms | -19.540
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 13ms| 16ms | 3ms | 22.315
| |  P99| 86ms| 91ms | 5ms | 5.780
| DraftStore.Get |  Avg| 14ms| 12ms | -2ms | -14.650
| |  P99| 158ms| 134ms | -24ms | -15.164
| DraftStore.GetDraftsForUser |  Avg| 14ms| 13ms | -1ms | -7.134
| |  P99| 145ms| 173ms | 28ms | 19.342
| DraftStore.Upsert |  Avg| 13ms| 12ms | -1ms | -7.669
| |  P99| 131ms| 109ms | -22ms | -16.854
| EmojiStore.GetByName |  Avg| 10ms| 9ms | -1ms | -10.317
| |  P99| 95ms| 90ms | -5ms | -5.276
| EmojiStore.GetMultipleByName |  Avg| 10ms| 3ms | -7ms | -68.964
| |  P99| 47ms| 10ms | -37ms | -77.895
| FileInfoStore.AttachToPost |  Avg| 20ms| 17ms | -3ms | -15.253
| |  P99| 192ms| 168ms | -24ms | -12.513
| FileInfoStore.Get |  Avg| 11ms| 10ms | -1ms | -8.843
| |  P99| 126ms| 100ms | -26ms | -20.582
| FileInfoStore.GetByIds |  Avg| 11ms| 10ms | -1ms | -9.297
| |  P99| 136ms| 93ms | -43ms | -31.694
| FileInfoStore.GetForPost |  Avg| 11ms| 10ms | -1ms | -9.420
| |  P99| 109ms| 98ms | -11ms | -10.129
| FileInfoStore.Save |  Avg| 14ms| 13ms | -1ms | -7.012
| |  P99| 142ms| 153ms | 11ms | 7.757
| FileInfoStore.SetContent |  Avg| 22ms| 22ms | 0s | 0.000
| |  P99| 211ms| 210ms | -1ms | -0.474
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 70ms| 71ms | 1ms | 1.425
| GroupStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 83ms| 82ms | -1ms | -1.199
| GroupStore.GetGroups |  Avg| 11ms| 10ms | -1ms | -9.382
| |  P99| 96ms| 94ms | -2ms | -2.083
| JobStore.Get |  Avg| 7ms| 5ms | -2ms | -27.826
| |  P99| 79ms| 44ms | -35ms | -44.034
| JobStore.GetAllByStatus |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 164ms| 175ms | 11ms | 6.694
| JobStore.GetCountByStatusAndType |  Avg| 12ms| 11ms | -1ms | -8.193
| |  P99| 187ms| 91ms | -96ms | -51.337
| JobStore.GetNewestJobByStatusesAndType |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 92ms| 94ms | 2ms | 2.186
| JobStore.Save |  Avg| 9ms| 10ms | 1ms | 10.730
| |  P99| 80ms| 82ms | 2ms | 2.516
| JobStore.UpdateOptimistically |  Avg| 7ms| 5ms | -2ms | -27.351
| |  P99| 47ms| 44ms | -3ms | -6.440
| JobStore.UpdateStatus |  Avg| 7ms| 5ms | -2ms | -26.683
| |  P99| 43ms| 41ms | -2ms | -4.634
| JobStore.UpdateStatusOptimistically |  Avg| 9ms| 7ms | -2ms | -21.509
| |  P99| 80ms| 64ms | -16ms | -20.091
| LinkMetadataStore.Get |  Avg| 10ms| 9ms | -1ms | -10.000
| |  P99| 97ms| 93ms | -4ms | -4.123
| LinkMetadataStore.Save |  Avg| 4ms| 6ms | 2ms | 48.079
| |  P99| 21ms| 43ms | 22ms | 107.314
| PluginStore.Delete |  Avg| 6ms| 5ms | -1ms | -17.682
| |  P99| 65ms| 56ms | -9ms | -13.765
| PluginStore.List |  Avg| 12ms| 9ms | -3ms | -24.294
| |  P99| 160ms| 169ms | 9ms | 5.625
| PluginStore.SetWithOptions |  Avg| 12ms| 11ms | -1ms | -8.165
| |  P99| 138ms| 99ms | -39ms | -28.313
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 8ms | 1ms | 13.640
| |  P99| 69ms| 98ms | 29ms | 42.104
| PostAcknowledgementStore.GetForPosts |  Avg| 14ms| 13ms | -1ms | -7.211
| |  P99| 192ms| 179ms | -13ms | -6.772
| PostPersistentNotificationStore.DeleteExpired |  Avg| 5ms| 4ms | -1ms | -18.487
| |  P99| 75ms| 39ms | -36ms | -47.692
| PostPersistentNotificationStore.Get |  Avg| 5ms| 4ms | -1ms | -18.366
| |  P99| 46ms| 23ms | -23ms | -50.094
| PostPersistentNotificationStore.GetSingle |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 89ms| 90ms | 1ms | 1.129
| PostPriorityStore.GetForPost |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 48ms| 84ms | 36ms | 74.410
| PostPriorityStore.GetForPosts |  Avg| 14ms| 13ms | -1ms | -6.977
| |  P99| 194ms| 181ms | -13ms | -6.705
| PostStore.AnalyticsPostCount |  Avg| 599ms| 474ms | -125ms | -20.876
| |  P99| 995ms| 498ms | -497ms | -49.950
| PostStore.Delete |  Avg| 25ms| 54ms | 29ms | 118.317
| |  P99| 209ms| 455ms | 246ms | 117.425
| PostStore.Get |  Avg| 25ms| 22ms | -3ms | -12.132
| |  P99| 230ms| 225ms | -5ms | -2.175
| PostStore.GetEtag |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 115ms| 99ms | -16ms | -13.904
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 72ms| 70ms | -2ms | -2.797
| PostStore.GetPostIdBeforeTime |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 95ms| 91ms | -4ms | -4.231
| PostStore.GetPostReminderMetadata |  Avg| 6ms| 13ms | 7ms | 108.886
| |  P99| 42ms| 188ms | 146ms | 345.555
| PostStore.GetPostReminders |  Avg| 8ms| 9ms | 1ms | 11.890
| |  P99| 42ms| 87ms | 45ms | 105.882
| PostStore.GetPosts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 80ms| 80ms | 0s | 0.000
| PostStore.GetPostsAfter |  Avg| 11ms| 10ms | -1ms | -9.481
| |  P99| 92ms| 105ms | 13ms | 14.183
| PostStore.GetPostsBefore |  Avg| 14ms| 13ms | -1ms | -7.221
| |  P99| 138ms| 121ms | -17ms | -12.277
| PostStore.GetPostsByThread |  Avg| 16ms| 14ms | -2ms | -12.867
| |  P99| 108ms| 95ms | -13ms | -11.985
| PostStore.GetPostsSince |  Avg| 28ms| 26ms | -2ms | -7.259
| |  P99| 213ms| 207ms | -6ms | -2.817
| PostStore.GetSingle |  Avg| 10ms| 9ms | -1ms | -10.126
| |  P99| 96ms| 91ms | -5ms | -5.219
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 36ms| 33ms | -3ms | -8.371
| |  P99| 358ms| 322ms | -36ms | -10.057
| PostStore.SearchPostsForUser |  Avg| 249ms| 247ms | -2ms | -0.804
| |  P99| 2.425s| 2.39s | -35ms | -1.443
| PostStore.SetPostReminder |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 420ms| 98ms | -322ms | -76.670
| PostStore.Update |  Avg| 33ms| 30ms | -3ms | -9.072
| |  P99| 225ms| 224ms | -1ms | -0.445
| PreferenceStore.DeleteCategoryAndName |  Avg| 10ms| 24ms | 14ms | 142.994
| |  P99| 86ms| 223ms | 137ms | 158.384
| PreferenceStore.Get |  Avg| 12ms| 11ms | -1ms | -8.408
| |  P99| 127ms| 101ms | -26ms | -20.444
| PreferenceStore.GetAll |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 96ms| 93ms | -3ms | -3.123
| PreferenceStore.Save |  Avg| 25ms| 23ms | -2ms | -7.947
| |  P99| 239ms| 234ms | -5ms | -2.089
| ProductNoticesStore.ClearOldNotices |  Avg| 45ms| 34ms | -11ms | -24.496
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 71ms| 69ms | -2ms | -2.805
| |  P99| 624ms| 610ms | -14ms | -2.243
| ReactionStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 87ms | -4ms | -4.381
| RoleStore.ChannelHigherScopedPermissions |  Avg| 21ms| 8ms | -13ms | -62.959
| |  P99| 179ms| 48ms | -131ms | -72.981
| RoleStore.GetByNames |  Avg| 0s| 11ms | 11ms | 1906363.903
| |  P99| 5ms| 49ms | 44ms | 888.885
| SessionStore.Get |  Avg| 17ms| 16ms | -1ms | -5.801
| |  P99| 206ms| 198ms | -8ms | -3.885
| SessionStore.GetLRUSessions |  Avg| 7ms| 6ms | -1ms | -14.384
| |  P99| 82ms| 74ms | -8ms | -9.703
| SessionStore.GetSessionsExpired |  Avg| 6ms| 3ms | -3ms | -51.396
| |  P99| 47ms| 9ms | -38ms | -80.851
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 79ms | -8ms | -9.214
| SessionStore.Remove |  Avg| 5ms| 7ms | 2ms | 36.792
| |  P99| 24ms| 86ms | 62ms | 259.686
| SessionStore.Save |  Avg| 15ms| 13ms | -2ms | -13.724
| |  P99| 160ms| 126ms | -34ms | -21.280
| SessionStore.UpdateLastActivityAt |  Avg| 11ms| 10ms | -1ms | -9.461
| |  P99| 91ms| 88ms | -3ms | -3.287
| StatusStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 76ms| 71ms | -5ms | -6.552
| StatusStore.GetByIds |  Avg| 13ms| 11ms | -2ms | -15.206
| |  P99| 154ms| 139ms | -15ms | -9.772
| StatusStore.SaveOrUpdate |  Avg| 17ms| 23ms | 6ms | 34.890
| |  P99| 230ms| 332ms | 102ms | 44.389
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 6ms| 5ms | -1ms | -15.447
| |  P99| 85ms| 43ms | -42ms | -49.412
| StatusStore.UpdateLastActivityAt |  Avg| 10ms| 9ms | -1ms | -10.286
| |  P99| 92ms| 90ms | -2ms | -2.173
| SystemStore.GetByName |  Avg| 7ms| 6ms | -1ms | -15.143
| |  P99| 83ms| 82ms | -1ms | -1.201
| SystemStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.Get |  Avg| 9ms| 8ms | -1ms | -10.992
| |  P99| 94ms| 89ms | -5ms | -5.342
| TeamStore.GetActiveMemberCount |  Avg| 84ms| 72ms | -12ms | -14.257
| |  P99| 243ms| 239ms | -4ms | -1.644
| TeamStore.GetAllPage |  Avg| 8ms| 7ms | -1ms | -13.031
| |  P99| 90ms| 89ms | -1ms | -1.105
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 9ms| 8ms | -1ms | -11.486
| |  P99| 92ms| 89ms | -3ms | -3.267
| TeamStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 49ms| 44ms | -5ms | -10.202
| TeamStore.GetTeamsByUserId |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 88ms | -2ms | -2.214
| TeamStore.GetTeamsForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.109
| TeamStore.GetTotalMemberCount |  Avg| 83ms| 67ms | -16ms | -19.368
| |  P99| 243ms| 243ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 45ms| 45ms | 0s | 0.000
| |  P99| 247ms| 247ms | 0s | 0.000
| ThreadStore.Get |  Avg| 9ms| 10ms | 1ms | 10.732
| |  P99| 87ms| 86ms | -1ms | -1.149
| ThreadStore.GetMembershipForUser |  Avg| 10ms| 9ms | -1ms | -10.098
| |  P99| 98ms| 92ms | -6ms | -6.116
| ThreadStore.GetTeamsUnreadForUser |  Avg| 12ms| 11ms | -1ms | -8.397
| |  P99| 149ms| 123ms | -26ms | -17.494
| ThreadStore.GetThreadFollowers |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 92ms | 3ms | 3.367
| ThreadStore.GetThreadForUser |  Avg| 19ms| 18ms | -1ms | -5.291
| |  P99| 200ms| 196ms | -4ms | -1.995
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 17ms| 16ms | -1ms | -5.874
| |  P99| 107ms| 97ms | -10ms | -9.331
| ThreadStore.GetThreadsForUser |  Avg| 14ms| 13ms | -1ms | -6.929
| |  P99| 149ms| 125ms | -24ms | -16.109
| ThreadStore.GetTotalThreads |  Avg| 9ms| 8ms | -1ms | -11.544
| |  P99| 92ms| 91ms | -1ms | -1.089
| ThreadStore.GetTotalUnreadMentions |  Avg| 9ms| 8ms | -1ms | -11.145
| |  P99| 92ms| 91ms | -1ms | -1.082
| ThreadStore.GetTotalUnreadThreads |  Avg| 9ms| 8ms | -1ms | -11.645
| |  P99| 90ms| 90ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 93ms| 91ms | -2ms | -2.151
| ThreadStore.MaintainMembership |  Avg| 22ms| 20ms | -2ms | -9.169
| |  P99| 228ms| 220ms | -8ms | -3.510
| ThreadStore.MarkAllAsReadByChannels |  Avg| 11ms| 8ms | -3ms | -27.937
| |  P99| 97ms| 93ms | -4ms | -4.121
| ThreadStore.MarkAllAsReadByTeam |  Avg| 14ms| 26ms | 12ms | 86.741
| |  P99| 49ms| 99ms | 50ms | 102.041
| ThreadStore.MarkAsRead |  Avg| 10ms| 9ms | -1ms | -9.660
| |  P99| 93ms| 87ms | -6ms | -6.478
| ThreadStore.UpdateMembership |  Avg| 10ms| 9ms | -1ms | -10.136
| |  P99| 91ms| 88ms | -3ms | -3.313
| TokenStore.Cleanup |  Avg| 12ms| 20ms | 8ms | 64.013
| |  P99| 49ms| 98ms | 49ms | 100.000
| UserAccessTokenStore.GetByToken |  Avg| 13ms| 8ms | -5ms | -39.224
| |  P99| 207ms| 78ms | -129ms | -62.244
| UserStore.AutocompleteUsersInChannel |  Avg| 76ms| 72ms | -4ms | -5.241
| |  P99| 362ms| 371ms | 9ms | 2.484
| UserStore.Count |  Avg| 23ms| 18ms | -5ms | -21.356
| |  P99| 92ms| 49ms | -43ms | -46.739
| UserStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 90ms| 86ms | -4ms | -4.435
| UserStore.GetAllProfiles |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 63ms| 62ms | -1ms | -1.578
| UserStore.GetAllProfilesInChannel |  Avg| 458ms| 434ms | -24ms | -5.235
| |  P99| 2.279s| 2.22s | -59ms | -2.589
| UserStore.GetByUsername |  Avg| 10ms| 12ms | 2ms | 19.098
| |  P99| 97ms| 161ms | 64ms | 65.979
| UserStore.GetForLogin |  Avg| 8ms| 7ms | -1ms | -13.090
| |  P99| 87ms| 85ms | -2ms | -2.302
| UserStore.GetMany |  Avg| 18ms| 5ms | -13ms | -73.326
| |  P99| 233ms| 46ms | -187ms | -80.341
| UserStore.GetProfileByIds |  Avg| 12ms| 11ms | -1ms | -8.491
| |  P99| 136ms| 103ms | -33ms | -24.223
| UserStore.GetProfilesByUsernames |  Avg| 13ms| 12ms | -1ms | -7.990
| |  P99| 135ms| 114ms | -21ms | -15.568
| UserStore.GetProfilesInChannel |  Avg| 36ms| 31ms | -5ms | -13.970
| |  P99| 238ms| 460ms | 222ms | 93.082
| UserStore.GetProfilesNotInChannel |  Avg| 22ms| 9ms | -13ms | -59.525
| |  P99| 223ms| 25ms | -198ms | -88.788
| UserStore.GetUnreadCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 93ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 42ms| 42ms | 0s | 0.000
| UserStore.Save |  Avg| 86ms| 86ms | 0s | 0.000
| |  P99| 354ms| 351ms | -3ms | -0.848
| UserStore.Search |  Avg| 56ms| 54ms | -2ms | -3.592
| |  P99| 237ms| 234ms | -3ms | -1.264
| UserStore.Update |  Avg| 24ms| 23ms | -1ms | -4.217
| |  P99| 208ms| 311ms | 103ms | 49.406
| UserStore.UpdateFailedPasswordAttempts |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 83ms | -5ms | -5.672
| UserStore.UpdateLastLogin |  Avg| 9ms| 8ms | -1ms | -11.349
| |  P99| 76ms| 70ms | -6ms | -7.872
| UserStore.UpdateUpdateAt |  Avg| 8ms| 9ms | 1ms | 11.868
| |  P99| 71ms| 74ms | 3ms | 4.235
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 84ms| 82ms | -2ms | -2.379
| WebhookStore.GetOutgoingByTeam |  Avg| 14ms| 13ms | -1ms | -7.117
| |  P99| 160ms| 146ms | -14ms | -8.764
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 664ms| 587ms | -77ms | -11.597
| | P99| 2.533s| 2.419s | -114ms | -4.500
| addTeamMember | Avg| 1.448s| 1.452s | 4ms | 0.276
| | P99| 8.104s| 8.053s | -51ms | -0.629
| autocompleteChannelsForTeamForSearch | Avg| 104ms| 103ms | -1ms | -0.957
| | P99| 443ms| 2.255s | 1.812s | 409.478
| autocompleteUsers | Avg| 71ms| 68ms | -3ms | -4.253
| | P99| 349ms| 358ms | 9ms | 2.578
| createCategoryForTeamForUser | Avg| 223ms| 106ms | -117ms | -52.416
| | P99| 249ms| 490ms | 241ms | 96.950
| createChannel | Avg| 913ms| 589ms | -324ms | -35.505
| | P99| 4.775s| 2.387s | -2.388s | -50.010
| createDirectChannel | Avg| 737ms| 736ms | -1ms | -0.136
| | P99| 3.8s| 2.448s | -1.352s | -35.578
| createGroupChannel | Avg| 1.274s| 1.155s | -119ms | -9.343
| | P99| 4.892s| 4.889s | -3ms | -0.061
| createPost | Avg| 891ms| 834ms | -57ms | -6.401
| | P99| 4.665s| 4.587s | -78ms | -1.672
| createUser | Avg| 334ms| 319ms | -15ms | -4.497
| | P99| 2.21s| 2.148s | -62ms | -2.805
| deleteDraft | Avg| 15ms| 14ms | -1ms | -6.744
| | P99| 180ms| 162ms | -18ms | -10.014
| deletePost | Avg| 45ms| 79ms | 34ms | 75.042
| | P99| 432ms| 478ms | 46ms | 10.636
| followThreadByUser | Avg| 76ms| 46ms | -30ms | -39.483
| | P99| 845ms| 243ms | -602ms | -71.238
| getAllTeams | Avg| 10ms| 9ms | -1ms | -10.296
| | P99| 134ms| 114ms | -20ms | -14.875
| getCategoriesForTeamForUser | Avg| 30ms| 43ms | 13ms | 43.749
| | P99| 234ms| 237ms | 3ms | 1.282
| getChannel | Avg| 34ms| 28ms | -6ms | -17.487
| | P99| 321ms| 243ms | -78ms | -24.327
| getChannelMember | Avg| 26ms| 12ms | -14ms | -54.834
| | P99| 245ms| 207ms | -38ms | -15.504
| getChannelMembers | Avg| 7ms| 27ms | 20ms | 269.373
| | P99| 25ms| 50ms | 25ms | 101.831
| getChannelMembersForTeamForUser | Avg| 14ms| 13ms | -1ms | -7.384
| | P99| 151ms| 138ms | -13ms | -8.584
| getChannelStats | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 110ms| 113ms | 3ms | 2.716
| getChannelUnread | Avg| 14ms| 11ms | -3ms | -21.878
| | P99| 182ms| 128ms | -54ms | -29.626
| getChannelsForTeamForUser | Avg| 14ms| 12ms | -2ms | -14.620
| | P99| 168ms| 151ms | -17ms | -10.136
| getChannelsForUser | Avg| 12ms| 10ms | -2ms | -16.968
| | P99| 140ms| 98ms | -42ms | -29.925
| getClientConfig | Avg| 22ms| 21ms | -1ms | -4.583
| | P99| 239ms| 232ms | -7ms | -2.934
| getDrafts | Avg| 15ms| 14ms | -1ms | -6.619
| | P99| 180ms| 194ms | 14ms | 7.764
| getFilePreview | Avg| 68ms| 65ms | -3ms | -4.388
| | P99| 374ms| 335ms | -39ms | -10.428
| getFileThumbnail | Avg| 56ms| 53ms | -3ms | -5.370
| | P99| 308ms| 255ms | -53ms | -17.212
| getPostThread | Avg| 61ms| 55ms | -6ms | -9.806
| | P99| 475ms| 454ms | -21ms | -4.420
| getPostsForChannel | Avg| 107ms| 103ms | -4ms | -3.724
| | P99| 1.059s| 991ms | -68ms | -6.421
| getPostsForChannelAroundLastUnread | Avg| 50ms| 49ms | -1ms | -2.019
| | P99| 461ms| 460ms | -1ms | -0.217
| getPreferences | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 100ms| 98ms | -2ms | -1.999
| getProfileImage | Avg| 84ms| 82ms | -2ms | -2.391
| | P99| 462ms| 460ms | -2ms | -0.433
| getPublicChannelsForTeam | Avg| 36ms| 32ms | -4ms | -11.122
| | P99| 238ms| 203ms | -35ms | -14.716
| getTeamMember | Avg| 13ms| 11ms | -2ms | -14.928
| | P99| 167ms| 129ms | -38ms | -22.809
| getTeamMembersForUser | Avg| 11ms| 10ms | -1ms | -9.501
| | P99| 147ms| 132ms | -15ms | -10.212
| getTeamStats | Avg| 107ms| 88ms | -19ms | -17.721
| | P99| 247ms| 244ms | -3ms | -1.215
| getTeamsForUser | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 93ms| 92ms | -1ms | -1.080
| getTeamsUnreadForUser | Avg| 17ms| 15ms | -2ms | -12.056
| | P99| 211ms| 200ms | -11ms | -5.225
| getThreadsForUser | Avg| 15ms| 14ms | -1ms | -6.631
| | P99| 176ms| 162ms | -14ms | -7.951
| getUser | Avg| 15ms| 15ms | 0s | 0.000
| | P99| 232ms| 228ms | -4ms | -1.725
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 44ms| 42ms | -2ms | -4.550
| getUsers | Avg| 14ms| 15ms | 1ms | 6.901
| | P99| 219ms| 222ms | 3ms | 1.370
| getUsersByIds | Avg| 4ms| 3ms | -1ms | -28.538
| | P99| 47ms| 45ms | -2ms | -4.259
| getUsersByNames | Avg| 13ms| 12ms | -1ms | -7.533
| | P99| 155ms| 140ms | -15ms | -9.690
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 227ms| 210ms | -17ms | -7.498
| | P99| 2.123s| 2.025s | -98ms | -4.616
| logout | Avg| 131ms| 138ms | 7ms | 5.341
| | P99| 425ms| 477ms | 52ms | 12.236
| patchPost | Avg| 112ms| 110ms | -2ms | -1.786
| | P99| 830ms| 645ms | -185ms | -22.289
| removeUserCustomStatus | Avg| 425ms| 432ms | 7ms | 1.647
| | P99| 2.085s| 2.25s | 165ms | 7.914
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 38ms| 35ms | -3ms | -7.827
| | P99| 279ms| 247ms | -32ms | -11.486
| searchAllChannels | Avg| 61ms| 60ms | -1ms | -1.631
| | P99| 240ms| 242ms | 2ms | 0.834
| searchGroupChannels | Avg| 15ms| 19ms | 4ms | 27.051
| | P99| 163ms| 140ms | -23ms | -14.107
| searchPostsInTeam | Avg| 277ms| 275ms | -2ms | -0.723
| | P99| 2.476s| 2.399s | -77ms | -3.110
| searchUsers | Avg| 59ms| 57ms | -2ms | -3.414
| | P99| 240ms| 238ms | -2ms | -0.832
| setPostReminder | Avg| 72ms| 82ms | 10ms | 13.971
| | P99| 840ms| 246ms | -594ms | -70.718
| unfollowThreadByUser | Avg| 56ms| 57ms | 1ms | 1.782
| | P99| 413ms| 454ms | 41ms | 9.927
| updateCategoriesForTeamForUser | Avg| 212ms| 275ms | 63ms | 29.665
| | P99| 1.585s| 2.095s | 510ms | 32.173
| updatePreferences | Avg| 42ms| 36ms | -6ms | -14.304
| | P99| 394ms| 320ms | -74ms | -18.779
| updateReadStateAllThreadsByUser | Avg| 14ms| 26ms | 12ms | 85.894
| | P99| 49ms| 99ms | 50ms | 102.041
| updateReadStateThreadByUser | Avg| 142ms| 132ms | -10ms | -7.051
| | P99| 905ms| 876ms | -29ms | -3.205
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 20ms | 15ms | 301.182
| uploadFileStream | Avg| 475ms| 457ms | -18ms | -3.787
| | P99| 2.188s| 2.148s | -40ms | -1.828
| upsertDraft | Avg| 16ms| 15ms | -1ms | -6.135
| | P99| 192ms| 188ms | -4ms | -2.084
| viewChannel | Avg| 45ms| 42ms | -3ms | -6.633
| | P99| 433ms| 418ms | -15ms | -3.467
